<script>

  let licenses = [
    "Meth License",
    "Copper License",
    "Copper License"
  ];
</script>

<main class="license_container">
  <div class="license_menu">
    <div class="license_menu_title">
      FRAG LICENSES
    </div>
    <div class="license_menu_header">
      Licenses Owned
    </div>
    {#each licenses as license}
      <div class="a_license">
        <h1>{license}</h1>
      </div>
    {/each}
  </div>
</main>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap');

  .license_container {
    width: 100%;
    height: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
    background: linear-gradient(135deg, #6a11cb 0%, #2575fc 100%);
    font-family: 'Roboto', sans-serif;
  }

  .license_menu {
    width: 22rem;
    height: 35rem;
    background: rgba(255, 255, 255, 0.2);
    border-radius: 1rem;
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
    backdrop-filter: blur(10px);
    overflow: hidden;
  }

  .license_menu_title {
    background: rgba(0, 0, 0, 0.5);
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.8rem;
    font-weight: 700;
    color: #ffffff;
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.2);
  }

  .license_menu_header {
    background: rgba(0, 0, 0, 0.3);
    width: 100%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 1.2rem;
    font-weight: 500;
    color: #ffffff;
  }

  .a_license {
    width: 100%;
    background: rgba(255, 255, 255, 0.1);
    box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
    font-size: 1rem;
    font-weight: 400;
    color: #ffffff;
    transition: background 0.3s ease;
    margin-bottom: 1%;
  }
  .a_license:last-child {
    margin-bottom: 0;
  }

  .a_license:hover {
    background: rgba(255, 255, 255, 0.2);
  }

  h1 {
    margin: 0;
    font-size: 1.2rem;
    font-weight: 400;
  }
</style>
