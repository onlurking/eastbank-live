<script>
  import Logo from "../assets/easybank.svg";
  import Menu from "../assets/menu.svg";
</script>

<nav class="navbar">
  <div class="navbar__wrapper">
    <img src={Logo} alt="logotipo" class="navbar__logo" />
    <img src={Menu} alt="logotipo" class="navbar__logo" />
  </div>
</nav>

<style>
  .navbar {
    background-color: var(--white);
  }

  .navbar__wrapper {
    display: flex;
    justify-content: space-between;
    padding: 24px;
  }

  .navbar__logo {
    margin-top: 22px;
    margin-bottom: 22px;
    margin-left: 24px;
  }
</style>
