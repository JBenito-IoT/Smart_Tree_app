<template>
  <footer class="footer">
    <div class="container-fluid">
      <ul class="nav">
        <li class="nav-item">
          <a
            href=""
            target="_blank"
            rel="noopener"
            class="nav-link"
          >
            Green IoT
          </a>
        </li>
        <li class="nav-item">
          <a
            href=""
            target="_blank"
            rel="noopener"
            class="nav-link"
          >
            About Us
          </a>
        </li>
        <li class="nav-item">
          <a
            href=""
            target="_blank"
            rel="noopener"
            class="nav-link"
          >
            Blog
          </a>
        </li>
      </ul>
      <div class="copyright">
        &copy; {{ year }}, made for <i class="tim-icons icon-heart-2"></i> by
        
        <a
          href=""
          target="_blank"
          rel="noopener"
          >JBenito</a
        >
        for a better life.
      </div>
    </div>
  </footer>
</template>
<script>
export default {
  data() {
    return {
      year: new Date().getFullYear()
    };
  }
};
</script>
<style></style>
