<script>
  import svelteLogo from './assets/svelte.svg'
  import viteLogo from '/vite.svg'
  import Counter from './lib/Counter.svelte'
</script>

<main class = "license_container">
  <div class = "license_menu">
    <div class = "license_menu_title">
      FRAG LICENSES
    </div>
    <div class = "license_menu_header">
      Licenses Owned
    </div>
    <div class = "a_license">
      <h1>Meth License</h1>
    </div>
  </div>
</main>

<style>
 .license_container {
  width: 100%;
  height: 100%;
  display: flex;
  justify-content: center;
  align-items: center;
 }
 .license_menu {
  width: 20%;
  height: 70%;
  background: rgba(9, 8, 32, 0.247);
  border-radius: 1vh;
  display: flex;
  overflow: hidden;
  flex-direction: column;
  align-items: center;
  text-align: center;
  justify-content: flex-start;
 }
 .license_menu_title {
  background: rgba(0, 0, 0, 0.247);
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 3vh;
    font-weight: 900;
    text-shadow: 1px 1px 8px #ffffff70;
    padding-block: 2%;
 }
 .license_menu_header{
  background: rgba(0, 0, 0, 0.445);
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: center;
  font-size: 1.8vh;
  font-weight: 600;
  text-shadow: 1px 1px white;
  padding-block: 1%;
 }
 .a_license {
  width: 100%;
  font-size: 0.6vh;
 }
</style>
