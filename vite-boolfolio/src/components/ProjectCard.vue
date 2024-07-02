<template>
    <div class="card">
      <h2>{{ project.title }}</h2>
      <p>{{ project.description }}</p>
    </div>
  </template>
  
  <script>
  export default {
    props: {
      project: {
        type: Object,
        required: true
      }
    }
  }
  </script>
  
  <style>
  .card {
    border: 1px solid #ccc;
    padding: 16px;
    margin: 16px 0;
  }
  </style>
  