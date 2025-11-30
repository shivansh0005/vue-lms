<template>
  <header class="navbar">
    <div class="navbar-inner container">
      <div class="brand">Vue LMS</div>

      <nav class="nav-actions">
        <button class="btn btn-primary">Login</button>
      </nav>
    </div>
  </header>
</template>

<script setup>
</script>

<style scoped>
.navbar {
  height: var(--nav-height);
  background: var(--color-primary);
  color: white;
  display: flex;
  align-items: center;
  box-shadow: var(--shadow-sm);
}

.navbar-inner {
  width: 100%;
  display: flex;
  align-items: center;
  justify-content: space-between;
}

.brand {
  font-size: 1.25rem;
  font-weight: bold;
}

.btn {
  padding: 8px 16px;
  border-radius: var(--radius);
  border: none;
  cursor: pointer;
  font-size: 0.95rem;
  font-weight: 500;
}

.btn-primary {
  background: white;
  color: var(--color-primary);
}

@media (max-width: 600px) {
  .nav-actions {
    display: none;
  }
}
</style>
