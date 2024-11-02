# Personal-Blog-Website
This project required to utilize HTML and CSS skills to build out a personal blog website, including custom images, layout, and styling. 

//css
*{
    margin: 3px; 
    padding: 0;
    box-sizing: border-box;
    text-decoration: none;
   }


   header{
    margin: 0.5px;
    padding-left: 20px;
    text-align: center;
   }

   .main{
     display: flex;
     flex: 1;
   }

   h3{
    text-align: center;
   }
   .h3-1{
    font-size: smaller;
    font-style: italic;
   }

   

   p{
    font-size: small;
    text-align: start;
   }
   .p{
    text-decoration: underline;
    font-weight: bolder;
    font-size: 15px;
   }

   img{
    max-width: 50%;
    max-height: 50%;
    margin: auto;
    display: block;
   }
   
   figcaption {
    font-size: 15px;
    padding: 0px;
   }

   footer{
    background-color: antiquewhite;
    display: flex;
    flex-direction: row;
    justify-content: center;
    gap: 10px;
    
    }
   
   ul {
    display: flex;
    justify-content: center;
    cursor: pointer;
   }
    
    ul li{
      display: inline-block;
      transition: all 0.3s ease;

    }

    ul li:hover {
      background-color: blue;
    }
    
    ul li a{
       color: black;
       width: 100%;
       height: 100%;
    }



   body {
    
    font-size: 24px;
    display: flex;
    text-align: center;
    flex-direction: column;

   }

   @media(max-width: 500px) {

    .body{
      display: grid;
      
    }
    .blog-container{
      display: grid;
      grid-template-columns: 1fr;
      grid-area: "hd hd"
      "feat feat"
      "main main"
      "ft ft";
  
    }
}

//style css

@import url('css/blog-post.css');
@import url('css/footer.css');
@import url('css/homepage.css');

body {
    
    display: block;

   }

   img {
    display: block;
    margin: auto;
  }

  //homepage

  *{
    margin: 0; padding: 0;
    box-sizing: border-box;
    text-decoration: none;
   }
   
   header {
    position: start;
    display: flex;
    
    background-color: antiquewhite;
    padding: 10px;
    font-size: 20px;
    margin-bottom: 100px;
    justify-content: space-between;
    align-items: center;
    
  
   }
  
   .header{
    font-size:larger;
   }
  
   header .navbar ul {
    list-style: none;
    float: right;
  
    
   }
  
   header .navbar ul li {
    position: relative;

   
   }
  
  
   
   header .navbar ul li a  {
    font-size: 18px;
    padding: 15px;
    color: black;
    display: flex;
    flex-direction: row;
    justify-content: center;
    position:relative;
   
   }
   
  
   header .navbar ul li a:hover{
    background-color: black;
    color: white;
    
   }
   
   
  img {
    display: block;
    margin: auto;
    max-width: 100%;
  }

  .fitted-image{
    width: 150px;
    height: 150px;
  }
  
   
  
   header label{
    font-size: 23px;
    cursor: pointer;
    display: none;
  
   }
   
   
   
  
   .blog-container {
      display: grid;
      flex-direction: row;
      align-items: center;
      grid-template-columns: 1fr 1fr;
      gap: 20px;
      
      
    }
  
   .blog-post {
     display: block;
     background-color:antiquewhite;
     padding: 50px;
     margin: 20% auto;
     text-align: start;
     box-shadow: 2px 2px black;
     
   }
  .blog-post .post-title{
    align-content: baseline;
    padding: 20px;
  }
  
  blog-post .link {
    text-decoration:underline;
  }
  
  
  
  .blog-post  h2 {
    display: flex;
    flex-direction: column;
    text-align:center;
    align-items:stretch;
    justify-content: space-evenly;
    padding:0 ;
    margin: 0 ;
   }
  
  
  
  
   footer{
    
    background-color: antiquewhite;
    display: flex;
    flex-direction: row;
    justify-content: center;
    gap: 10px;
    font-size: 20px;
    
    }
   ul {
    display: flex;
    justify-content: center;
    align-items: center;
    cursor: pointer;
   }
    
    .ul li{
      display: inline-block;
      padding: 5px;
      transition: all 0.3s ease;
  
    }
  
    .ul li:hover {
      background-color: blue;
    }
    
    .ul li a{
       color: black;
       width: 50%;
       height: 50%;
       font-size: 10px;
      
    }
    
    
  
    
    @media(max-width: 500px) {
  
    
   
      header{
        display: block;
        grid-template-columns: 200px ;
        grid-template-rows: 1fr;
        grid-template-areas: "hd";
        
       
        
        height: 150px;
        padding: 20px;
       }
      
    
      .navbar ul li a{
        font-size: 20px;
      }
    
      
    
      
      body{
        display: block;
        
      }
      .blog-container{
        display: grid;
        grid-template-columns: 1fr;
        grid-area: "hd hd"
        "feat feat"
        "main main"
        "ft ft";
    
      }
    }
