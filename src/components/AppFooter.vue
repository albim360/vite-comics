<template>
    <footer class="page-footer">
      <section class="footer-link">
       <div class="container">
        <div class="row">
            <div class="col-2">
                <h2>DC COMICS</h2>
                <ul>
                    <li><a href="#">Characters</a></li>
                    <li><a href="#"></a></li>
                    <li><a href="#"></a></li>
                    <li><a href="#"></a></li>
                    <li><a href="#"></a></li>
                    <li><a href="#"></a></li>
                    <li><a href="#"></a></li>
                </ul>
                <div class="col-2">
                    <h2>DC COMICS</h2>
                    <ul>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#"></a></li>
                        <li><a href="#"></a></li>
                        <li><a href="#"></a></li>
                        <li><a href="#"></a></li>
                        <li><a href="#"></a></li>
                        <li><a href="#"></a></li>
                    </ul>
                </div> <div class="col-2">
                    <h2>DC COMICS</h2>
                    <ul>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#"></a></li>
                        <li><a href="#"></a></li>
                        <li><a href="#"></a></li>
                        <li><a href="#"></a></li>
                        <li><a href="#"></a></li>
                        <li><a href="#"></a></li>
                    </ul>
                </div> <div class="col-2">
                    <h2>DC COMICS</h2>
                    <ul>
                        <li><a href="#">Characters</a></li>
                        <li><a href="#"></a></li>
                        <li><a href="#"></a></li>
                        <li><a href="#"></a></li>
                        <li><a href="#"></a></li>
                        <li><a href="#"></a></li>
                        <li><a href="#"></a></li>
                    </ul>
                </div>
            </div>
        </div>
       </div>
      </section>
      <section class="footer-social">
       
      </section>
    </footer>
  </template>
  
  <script>
  export default {
    name: "AppFooter"
  }
  </script>
  
  <style>
  body {
    height: 100vh;
    overflow: hidden;
  }
  
  footer {
    height: 600px; /* DEBUG */
    background-image: url(../../public/img/footer-bg.jpg);
    background-size: cover;
  }
  
  .footer-link {
    height: calc(100% - 132px); 
    margin: 0 180px;
    background-image: url(../../public/img/dc-logo-bg.png);
    background-repeat: no-repeat;
    background-size: 40%;
    background-position: right;
  }

  .row {
    align-items: center;
  }
  
  .footer-social {
    height: 104px;
    background-color: #303030;
  }

  footer .container {
    padding: 20px;
  }

  footer h2 {
    color: white;
    font-weight: bold;
  }

  footer ul {
    padding: 10px;
  }
  
  footer li {
    text-align: left;
  }
  </style>
  