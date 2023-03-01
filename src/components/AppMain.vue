<template>
   <main class="main-content">
    <div class="container">
        <p>Content goes here</p>
    </div>
   </main>
  </template>
  
  <script>
  export default {
    name: "AppMain"
  }
  </script>
  
  <style>
  .main-content {
    background-color: black;
    min-height: 130px; 
    color: white; 
    padding: 25px;
  }

  .container > p {
    font-size: 24px;
  }


  </style>
  