<script>
export default {
  data() {
    return {
      comics: [
        {
          thumb: "https://www.coverbrowser.com/image/action-comics/1-1.jpg",
          price: "$19.99",
          series: "Action Comics",
          type: "comic book",
        },
        {
          thumb: "https://www.panini.it/media/catalog/product/cache/a5b5dd3adfe0d321084804c738f29601/M/1/M1BLLA015ISBN_0.jpg",
          price: "$3.99",
          series: "American Vampire 1976",
          type: "comic book",
        },
        {
          thumb: "https://media.wired.com/photos/593384dad80dd005b42b2817/master/w_2560%2Cc_limit/Aquaman-16.jpg",
          price: "$16.99",
          series: "Aquaman",
          type: "graphic novel",
        },
        {
          thumb: "https://d29xot63vimef3.cloudfront.net/image/batgirl/1-1.jpg",
          price: "$2.99",
          series: "Batgirl",
          type: "comic book",
        },
        {
          thumb: "https://static.posters.cz/image/750/locandine-film-in-plexiglass-batman-prowl-comic-cover-i69653.jpg",
          price: "$3.99",
          series: "Batman",
          type: "comic book",
        },
        {
          thumb: "https://static.wikia.nocookie.net/marvel_dc/images/5/50/Batman_Beyond_v.1_1.jpg",
          price: "$2.99",
          series: "Batman Beyond",
          type: "comic book",
        },
        {
          thumb: "https://static.wikia.nocookie.net/marvel_dc/images/0/0d/Batman_Superman_Vol_1_1.jpg",
          price: "$3.99",
          series: "Batman/Superman",
          type: "comic book",
        },
        {
          thumb: "https://static.wikia.nocookie.net/marvel_dc/images/c/cf/Batman_Superman_Annual_Vol_2_1.jpg",
          price: "$4.99",
          series: "Batman/Superman Annual",
          type: "comic book",
        },
        {
          thumb: "https://static.wikia.nocookie.net/marvel_dc/images/5/54/Batman_The_Joker_War_Zone_Vol_1_1.jpg",
          price: "$5.99",
          series: "Batman: The Joker War Zone",
          type: "comic book",
        },
        {
          thumb: "https://static.wikia.nocookie.net/marvel_dc/images/6/64/Batman_Three_Jokers_Collected.jpg",
          price: "$6.99",
          series: "Batman: Three Jokers",
          type: "comic book",
        },
        {
          thumb: "https://static.wikia.nocookie.net/marvel_dc/images/f/f8/Batman_White_Knight_Presents_Harley_Quinn_Vol_1_1.jpg",
          price: "$4.99",
          series: "Batman: White Knight Presents: Harley Quinn",
          type: "comic book",
        },
        {
          thumb: "https://static.wikia.nocookie.net/marvel_dc/images/c/c8/Catwoman_Vol_2_1.jpg",
          price: "$16.99",
          series: "Catwoman",
          type: "graphic novel",
        },
      ],
    };
  },
};
</script>

<template>
  <header>
    <div class="container">
      <div>
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

        <div class="content">
          <div class="comic-lista">
              <div v-for="(comic, index) in comics":key="index" class="comic-item">
                <img :src="comic.thumb" :alt="comic.series" class="comic-img"/>
                <h2 class="h2">
                  {{ comic.series }}
                </h2>
              </div>
          </div>
        </div>
        <button class="BUTTON-LOAD">
          LOAD MORE
        </button>
      </div>
      <div class="M-BLUE">
        <div>
          <ul>
            <li>
              <img class="IMG" src="/img/buy-comics-digital-comics.png" alt="DIGITAL">
              <a href="#">
                DIGITAL COMICS
              </a>
            </li>
            <li>
              <img class="IMG" src="/img/buy-comics-merchandise.png" alt="MERCHANDISING">
              <a href="#">
                DC MERCHANDISE
              </a>
            </li>
            <li>
              <img class="IMG" src="/img/buy-comics-subscriptions.png" alt="SUB">
              <a href="#">
                SUBSCRIPTION
              </a>
            </li>
            <li>
              <img class="IMG" src="/img/buy-comics-shop-locator.png" alt="SHOP">
              <a href="#">
                COMIC SHOP LOCATOR
              </a>
            </li>
            <li>
              <img class="IMG" src="/img/buy-dc-power-visa.svg" alt="POWER">
              <a href="#">
                DC POWER VISA
              </a>
            </li>
          </ul>

        </div>
      </div>

    </div>

  </main>
  <footer>
    <!--Colonna1-->
      <div class="F-top flex">
        <div class="PS">
        <ul>
        <li>
          <h4 class="h4">DC COMICS</h4>
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
          <h4 class="h4">SHOP</h4>
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
        <div class="PS">
        <ul>
          <li>
            <h4 class="h4">DC</h4>
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
        <div class="PS">
        <ul>
          <li>
            <h4 class="h4">SITES</h4>
          </li>
          <li>
            <a href="#">DC</a>
          </li>
          <li>
            <a href="##">MAD Magazine</a>
          </li>
          <li>
            <a href="###">DC Kids</a>
          </li>
          <li>
            <a href="####">DC Universe</a>
          </li>
          <li>
            <a href="#####">DC Power Visa</a>
          </li>
        </ul>
        </div>
        <div class="flex">
          <img class="POSIT" src="/img/dc-logo-bg.png" alt="DC">
        </div>
      </div>  
     <div class="F-bottom flex">
        <div>
          <button class="button">
            <h4 class="HH">SIGN-UP NOW!</h4>  
          </button>
        </div>
        <div class="flex">
          <div class="flex">
            <h4 class="h4B">FOLLOW US</h4>
          </div>
          <div class="flex">
              <div>
                <a class="af" href="#">
                    <img src="/img/footer-facebook.png" alt="facebook">  
                </a>  
              </div>
              <div>
                <a class="af" href="##">
                    <img src="/img/footer-twitter.png" alt="twitter">
                </a> 
              </div>
              <div>
                <a class="af" href="###">
                    <img src="/img/footer-youtube.png" alt="youtube"> 
                </a>  
              </div>
              <div>
                <a class="af" href="####">
                    <img src="/img/footer-pinterest.png" alt="pinteest">  
                </a> 
              </div>
              <div>
                <a class="af2" href="#####">
                    <img src="/img/footer-periscope.png" alt="periscope">  
                </a> 
              </div>
          </div>
        </div>
      
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
  background-color: black;
}
.BUTTON-LOAD {
  background-color: #0282f9;
  color: white;
  margin: 20px;
  width: 120px;
  height: 50px;
  margin-left: 800px;
}
.h2{
  font-size: 1rem;
}
.content {
  max-width: 1200px;
  margin: auto;
  padding: 20px;
}
.comic-lista {
  display: flex;
  flex-wrap: wrap;
  gap: 20px;
  justify-content: center;
}

.comic-item {
  background-color: black;
  color: white;
  border-radius: 8px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  width: 175px;
  text-align: center;
}

.comic-img {
  width: 100%;
  height: 200px;
  border-radius: 4px;
}

.M-BLUE{
  background-color: #0282f9;
}
.M-BLUE ul li a:hover{
  text-transform: uppercase;
  font-size: 1.5rem;
  color: yellow;
}
.M-BLUE {
  text-align: center;
  padding: 20px 0;
} 
.M-BLUE ul {
  list-style: none;
  padding: 10px;
  display: flex;
  align-items: center;
  justify-content: center;

}
.M-BLUE ul li {
  list-style: none;
  margin: 0 5px;
  padding: 10px;
  color: black;
  text-decoration: none;
  font-weight: bold;
  transition: all .2s ease-in-out;
  
}
.M-BLUE ul li {
  display: flex;
  list-style: none;
}
.M-BLUE ul li a {
  text-decoration: none;
  color: white;
  margin-top: 40px;
  margin-left: 10px;
}
.IMG{
  height: 100px;
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
  text-transform: uppercase;
  font-size: 0.7rem;
  
}
.F-top{
  background-image: url('/img/footer-bg.jpg');
  background-size: 100%;
  padding-bottom: 30px;
  
}
.F-bottom{
  background-color: #303030;
  padding: 20px;
  display: flex;
  justify-content: space-between;
}
.flex{
  display: flex;
}
.POSIT{
  margin-left: 350px;
  margin-top: 30px;
}
.af{
  margin: 10px;
}
.af2{
  margin-right: 100px;
  margin-left: 10px;
}
.h4{
  padding-top: 15px;
}
.h4B{
  color: #0282f9;
  margin-top: 10px;
}
.PS{
  padding-left: 100px;
}
.H{
  margin: 10px;
  padding: 10px;
}
.HH{
  margin: 10px;
}
button{
  color: white;
  background-color: #303030;
  border: 2px solid #0282f9;
  height: 40px;
  margin-left: 100px;
}

</style>
