body {
  align-items: center;
  justify-content: center;
  height: 100vh;
  font-family: Arial, sans-serif;
  margin: 10px 50px 20px; 
  padding: 10px 50px 20px;
  background: #ccc9c9;
  color: #6257a5;
  font-size: 1.2rem;
  line-height: normal;
}
  
  img {
    max-width : 80%; 
 }
  
  header {
    text-align: center;  
    min-height: 150px;
    background-color: rgb(165, 33, 177); 
    background-size: cover;
    overflow: auto;
    }

 h1 {
        display: inline-flex;
        line-height: 100%;
        color: #806565;
        text-transform: uppercase;
        font-size: 3rem;
        text-shadow:1px 2px red, 0 0 1em blue, 0 0 0.2em blue; 
    }

      nav {
        display: inline-block;
        width: 80%;
        padding: 3px 0;
      }

    
    nav img {
        width: 10%;
    }

    .grid {
      display: grid;
      grid-template-columns: 50% 50%;
      justify-content: space-between; 
      align-items: stretch; 
      row-gap: 20px; 
  }
  
  nav a:link, nav a:visited {
    background-color: rgba(97, 143, 204, 0.3);
    padding: 0.5rem 4rem;
    text-decoration: none;
    font-size: 1rem;
    line-height: normal;
    border-radius: 30px;
    color: #0101010;
    margin-right: 1em;
    word-break: break-all;
    white-space: pre-wrap;
    font-weight: bold;
  }
  nav a:hover {
    background-color: rgba(255,255,255,1);
    transition: 500ms;
    font-weight: bold;
  }
  nav a.active {
    background-color: rgb(99, 36, 91);
    color: rgb(139, 139, 185);
    font-weight: bold;
  }
  main {
    width: 100%;
    overflow: visible;  
  }
  aside.left {
    float: left;
    width: 10%;
    height: auto;
    display: block;
    background: #504d79;
    padding: 100px 100px 60px ;
  }
  
  section.right {
    float: right;
    width: 70%;
  }

  h2 {
    color: indianred; 
  }

  section {
    background-color: #ccc; 
  }

  a {
    color: #1a0d53; 
    background-color:whitesmoke; 
  }
