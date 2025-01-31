<template>
    <div class="card">
      <slot></slot>
    </div>
  </template>
  
  <script>
  export default {
    name: 'BaseCard'
  }
  </script>
  
  <style scoped>
  .card {
    padding: 20px 32px;
    border-radius: 16px 0px 0px 0px;
    background: rgba(11, 61, 97, 0.2);
    width: 100%;
  }
  </style>