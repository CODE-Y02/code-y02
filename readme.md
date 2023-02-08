<!DOCTYPE html>
<html>
  <head>
    <title>Parcel Sandbox</title>
    <meta charset="UTF-8" />
    <style>
      * {
        margin: 0;
        padding: 0;
      }
      .flexCOl {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: center;
        gap: 0.5rem;
      }
      .underlined {
        /* background-color: aquamarine; */
        padding: 0.5rem 0.2rem;
        border-bottom: 2px solid black;
      }
      .stack {
        display: inline-block;
        margin: 0.5rem;
        width: 80px;
        height: auto;
        /* background: blanchedalmond; */
        border: 1px solid lightskyblue;
        border-radius: 0.5rem;
        padding:0.2rem;  
        background:rgba(255,255,255,0.8)      
      }
      .stack img{
        object-fit: cover;      
      }
      p{
        margin:1rem;
      }
      a{
        margin: 1rem 0;
        padding:0.5rem;
        font-weight:2rem;
        cursor:pointer;
        border-radius:0.5rem;
      }
      a:hover{
        background:lightgreen;
        transition: ease-in 0.5s;
        color: blue;
      }
    </style>

  </head>

  <body>
    <div class="flexCOl">
      <h1 class="underlined">
        Yatharth Lakahte
      </h1>
      <h3 class="underlined">
        Full Stack Web Developer
      </h3>
      <a href="https://code-y02.github.io/" target="_blank" rel="noopener noreferrer">MY PORTFOLIO</a>
    </div>
    <div class="flexCol">
      <h3>My Stacks 👇</h3>
      <div class="stack">
        <img src="https://upload.wikimedia.org/wikipedia/commons/9/99/Unofficial_JavaScript_logo_2.svg" alt="Javascript" />
      </div>
      <div class="stack">
        <img src="https://upload.wikimedia.org/wikipedia/commons/f/f5/Typescript.svg" alt="typescript" />
      </div>
      <div class="stack">
        <img src="./assets/nodejs.svg" alt="#" />
      </div>
      <div class="stack">
        <img src="./assets/mongodb.svg" alt="#" />
      </div>
      <div class="stack">
        <img src="./assets/react.svg" width="300" alt="#" />
      </div>
      <div class="stack">
        <img src="./assets/redux.svg" alt="redux" />
      </div>
      <div class="stack">
        <img src="./assets/mysql.svg" alt="mysql" />
      </div>
      <div class="stack">
        <img src="./assets/html.svg" alt="html" />
      </div>
      <div class="stack">
        <img src="./assets/css.svg"   alt="css" />
      </div>
      <div class="stack">
        <img src="./assets/github.svg"   alt="css" />
      </div>
      <div class="stack" style="width:auto; height:60px">
        <img src="./assets/git.svg" height="80"    alt="css" />
      </div>
      <div class="stack" style="width:auto; height:60px" >
        <img src="./assets/express.svg" alt="express" />
      </div>
      <div class="stack" style="width:auto; height:60px;" >
        <img src="./assets/bootstrap.svg" alt="bootstarp" />
      </div>
    </div>

  </body>
</html>
