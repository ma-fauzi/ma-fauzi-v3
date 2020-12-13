<template>
  <div>
    <nav>
      <div class="container">
        <div class="nav-logo">
          <span class="nav-brand">M.A - Fauzi</span>
        </div>
        <ul class="nav">
          <li class="nav-item">
            <a href="#" class="nav-link">
              <span class="number">I. </span>
              About
            </a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link">
              <span class="number">II. </span>
              Experience
            </a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link">
              <span class="number">III. </span>
              Work
            </a>
          </li>
          <li class="nav-item">
            <a href="#" class="nav-link">
              <span class="number">IV. </span>
              Contact
            </a>
          </li>
          <li class="nav-item">
            <a href="#" class="btn btn-dark-outline">
              Resume
            </a>
          </li>
        </ul>
      </div>
    </nav>
  </div>
</template>

<script>
export default {
  name: "Navbar",
};
</script>

<style lang="scss" scoped>
@import "../assets/styles/main.scss";

nav {
  width: 100vw;
  padding: 1.6rem 0;
  background-color: rgba($color: white, $alpha: 0.7);
  box-shadow: 0 0 10px 0 rgba($color: #000000, $alpha: 0.3);
  backdrop-filter: blur(10px);
}

.container {
  width: 90vw;
  display: flex;
  margin: auto;
  justify-content: space-between;
  align-items: center;
}

.nav {
  width: 45%;
  display: flex;
  justify-content: space-between;

  .nav-item {
    .nav-link {
      list-style: none;
      text-decoration: none;
      color: $dark-color;
      transition: 0.2s;

      .number {
        color: $primary-color;
      }

      &:hover {
        color: $primary-color;
      }
    }
  }
}
</style>
