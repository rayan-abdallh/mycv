<template>
  <nav>
    <!-- <router-link to="/">Home</router-link> |
    <router-link to="/about">About</router-link> -->
    <!-- Navbar -->
    <div class="navbar">
      <div class="container flex">
        <img class="logo" alt="Vue logo" src="logo2.jpeg">
        
        <nav>
          <ul>
          
            
         
            <li><a href="#home">HOME</a></li>
            <li><a href="#create cv">CREATE-CV</a></li>
            <li><a href="#bautus">BAUTUS</a></li>
            <li><a href="/login">LOGIN</a></li>
            <li><a href="#en">EN🌍</a></li>
          </ul>
        </nav>
      </div>
    </div>
    
 


  </nav>


  
  <router-view/>



 <!-- footer -->
 <footer class="footer bg-dark py-5">
      <div class="container grid grid-3">
        <div>
          <h1>Loruki</h1>
          <p>
            Copyright &copy;
            <!-- <script>
              document.write(new Date().getFullYear());
            </script> -->
          </p>
        </div>
        <nav>
          <ul>
            <li><a href="#demo">Demo</a></li>
            <li><a href="#features">Features</a></li>
            <li><a href="#docs">Docs</a></li>
          </ul>
        </nav>
        <div class="social">
          <a href="#"><i class="fab fa-github fa-2x"></i></a>
          <a href="#"><i class="fab fa-facebook fa-2x"></i></a>
          <a href="#"><i class="fab fa-instagram fa-2x"></i></a>
          <a href="#"><i class="fab fa-twitter fa-2x"></i></a>
        </div>
      </div>
    </footer>


</template>

<style>
.showcase-form{
  height: 558px;
width: 402px;
}

</style>
