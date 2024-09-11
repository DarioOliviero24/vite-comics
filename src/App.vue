<script>

</script>

<template>
  <header>
    <div class="container">
      <div>
        <div>

        </div>
        <div>
         <ul>
            <li>
                <img src="/img/dc-logo.png" alt="Logo">
            </li>
            <li>
              <a href="#">
                <h4>CHARACTERS</h4>

              </a>
              

            </li>
            <li>
              <a href="#">
                <h4>COMICS</h4>
              </a>
              

            </li>
            <li>
              <a href="#">
                <h4>MOVIES</h4>
              </a>
             
            </li>
            <li>
              <a href="#">
                <h4>TV</h4>
              </a>
              

            </li>
            <li>
              <a href="#">
                <h4>GAMES</h4>

              </a>
              

            </li>
            <li>
              <a href="#">
                <h4>COLLECTIBLES</h4>

              </a>
              

            </li>
            <li>
              <a href="#">
                <h4>VIDEOS</h4>

              </a>
              

            </li>
            <li>
              <a href="#">
                <h4>FANS</h4>

              </a>
              

            </li>
            <li>
              <a href="#">
                <h4>NEWS</h4>

              </a>
              

            </li>
            <li>
              <a href="#">
                <h4>SHOP</h4>

              </a>
              

            </li>
         </ul>
      </div>
      </div>
      

    </div>
     
  </header>
  <main>
    <div>
      <div class="M-top">
        
      </div>
      <div class="M-bottom">
        <div>
          
        </div>

      </div>

    </div>

  </main>
  <footer>
    <!--Colonna1-->
     <div class="F-top">
      <div>
        <ul>
        <li>
          <h4>DC COMICS</h4>
        </li>
        <li>
          <a href="#">Characters</a>
        </li>
        <li>
          <a href="##">Comics</a>
        </li>
        <li>
          <a href="###">Movies</a>
        </li>
        <li>
          <a href="####">TV</a>
        </li>
        <li>
          <a href="#####">Games</a>
        </li>
        <li>
          <a href="######">Videos</a>
        </li>
        <li>
          <a href="#######">News</a>
        </li>
       </ul>
       <ul>
        <li>
          <h4>SHOP</h4>
        </li>
        <li>
          <a href="#">Shop DC</a>
        </li>
        <li>
          <a href="##">Shop DC Collectibles</a>
        </li>
       </ul>
      </div>
      <!--Colonna2-->
      <div>
        <ul>
          <li>
            <h4>DC</h4>
          </li>
          <li>
            <a href="#">Terms Of Use</a>
          </li>
          <li>
            <a href="##">Privacy policy (New)</a>
          </li>
          <li>
            <a href="###">Ad Choices</a>
          </li>
          <li>
            <a href="####">Advertising</a>
          </li>
          <li>
            <a href="#####">Jobs</a>
          </li>
          <li>
            <a href="######">Subscriptions</a>
          </li>
          <li>
            <a href="#######">Talent Workshops</a>
          </li>
          <li><a href="########">CPSC Certificates</a></li>
          <li>
            <a href="#########">Ratings</a>
          </li>
          <li>
            <a href="##########">Shop Help</a>
          </li>
          <li>
            <a href="###########">Contact Us</a>
          </li>
        </ul>
      </div>
      <!--Colonna3-->
      <div>
        <ul>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
          <li></li>
        </ul>
      </div>

     </div>
      
     <div>
      

     </div>
  </footer>

</template>

<style scoped>
header {
  text-align: center;
  padding: 20px 0;
} 
header ul {
  list-style: none;
  padding: 10px;
  display: flex;
  align-items: center;
  justify-content: center;

}
header ul li {
  list-style: none;
  margin: 0 5px;
  padding: 10px;
  color: black;
  text-decoration: none;
  font-weight: bold;
  transition: all .2s ease-in-out;
  
}
header ul li {
  display: flex;
  list-style: none;
}
header ul li a {
  text-decoration: none;
  color: black;
}
header ul li a:hover,
header ul li a.active{
  color: #0282f9;
  text-transform: uppercase;
  font-size: 1.5rem;
  
}
.M-top{
  height: 400px;
  background-image: url('/img/jumbotron.jpg');
}
.M-bottom{
  height: 600px;
  background-color: black;
}
footer {
  text-align: center;
} 
footer ul {
  list-style: none;
  padding: 0;
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;

}
footer ul li {
  list-style: none;
  margin: 0 5px;
  padding: 10px;
  color: white;
  text-decoration: none;
  font-weight: bold;
  transition: all .2s ease-in-out;
  
}
footer ul li {
  display: flex;
  list-style: none;
}
footer ul li a {
  text-decoration: none;
  color: grey;
}
footer ul li a:hover,
footer ul li a.active{
  color: #0282f9;
  
}
.F-top{
  height: 420px;
  background-image: url('/img/footer-bg.jpg');
  
}
</style>
