<template>
  <div class="about">
    <div class="logo-container">
      <img alt="Vue logo" class="logo" src="@/assets/vjsparis.png" width="500" />
    </div>
  </div>
</template>

<style>
.logo-container {
  display: inline-block;
  animation: bounce 4s infinite ease-in-out;
}

.logo {
  width: 500px;
  display: block;
}

@keyframes bounce {
  0%, 100% {
    transform: translateY(0);
  }
  50% {
    transform: translateY(-20px);
  }
}

@media (min-width: 1024px) {
  .about {
    min-height: 100vh;
    display: flex;
    align-items: center;
  }
}
</style>
