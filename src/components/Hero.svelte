<script>
  import Shadow from "../assets/shadow.svg";
</script>

<section class="hero">
  <div class="hero__wrapper">
    <picture class="hero__image">
      <source media="(max-width: 799px)" srcset="images/mobile.png" />
      <source media="(min-width: 800px)" srcset="images/desktop.png" />
      <img src="images/mobile.png" alt="AEHUAEHUEHUAEHU KKK" />
    </picture>
    <img src={Shadow} alt="" class="hero__shadow" />
  </div>

  <div class="hero__content">
    <h2 class="hero__title">Next generation digital banking</h2>
    <p class="hero__body">
      Take your financial life online. Your Easybank account will be a
      one-stop-shop for spending, saving, budgeting, investing, and much more.
    </p>

    <button class="hero__button">Request Invite</button>
  </div>
</section>

<style lang="postcss">
  .hero__button {
    background: linear-gradient(135deg, #33d35e 0%, #2ab6d9 99.58%);
    border-radius: 22px;
    border: 0;
    color: var(--white);
    font-size: 14px;
    font-weight: 700;
    line-height: 28px;
    margin-top: 32px;
    padding: 8px 34px;
  }

  .hero__content {
    padding: 24px;
    text-align: center;
  }

  .hero__body {
    color: var(--grey);
    font-size: 15px;
    line-height: 25px;
    margin-top: 16px;
  }

  .hero__title {
    color: var(--text);
    font-size: 40px;
    font-weight: 300;
    line-height: 47px;
  }

  .hero__image {
    width: 100%;

    & > img {
      width: 100%;
    }
  }

  .hero__shadow {
    left: 0;
    position: absolute;
    z-index: -1;
  }
  .hero__wrapper {
    position: relative;
    z-index: 0;
  }
</style>
