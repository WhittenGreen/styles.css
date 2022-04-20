#background-video {
  width: 100vw;
  height: 100vh;
  object-fit: cover;
  position: fixed;
  left: 0;
  right: 0;
  top: 0;
  bottom: 0;
  z-index: -1;
}


   

body{
  font-family: 'Press Start 2P', cursive;
}

nav {
  font-family: 'Press Start 2P', cursive;
}

h1{
    text-align: center;
    margin: 0px auto;
    display: block;
    color: #00000070;
    font-family: 'Press Start 2P', cursive;
};

/* unvisited link */
a:link {
  color: red;
}

/* visited link */
a:visited {
  color: black;
}

/* mouse over link */
a:hover {
  color: hotpink;
}

/* selected link */
a:active {
  color: blue;
}


.card-title {
    text-align: center;
    
  }

col {
  padding-top: 10%;
}  
.card {
  
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 10px;
    grid-auto-rows: minmax(100px, auto);
    width: 30rem;

}




