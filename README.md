@import url('https://fonts.googleapis.com/css2?family=GFS+Didot&family=Young+Serif&display=swap');
/* */
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    list-style: none;
    outline: none;
    border: none;
    text-decoration: none;

}

html {
    width: 100vw;
    height: 100vh;
    font-size: 62.5%;
    font-family: 'GFS Didot', sans-serif;
    overflow-x: hidden;
    scroll-behavior: smooth;
}

/* MENU */



.content {
    width: 100vw;
    height: 70px;
    display: flex;
    justify-content: space-around;
    align-items: center;
    background-color: rgb(27, 26, 26);
    position: fixed;
    padding-left: 30rem;
}

.logo {
    width: 70px;
    height: auto;
    cursor: pointer;
    display: flex;
    align-items: center;
}


.logo h3 {
   color: white;
   font-size: 1.6rem;
  float: left;
 
}


.logo img {
    width: 100%;
    height: 100%;
    float: left !important;
    position: relative;



  
}

.content .list-menu {
    width: 600px;
    display: flex;
    align-items: center;
    justify-content: space-between;
}

.content .list-menu li a{
    padding-top: 3rem;
    padding-bottom: 2rem;
    padding-left: 1rem;
    padding-right: 1rem;
    color: rgb(255, 255, 255);
    font-size: 1.8rem;
    text-transform: uppercase;
    font-weight: 500;
    transition: all 200ms ease-in;
}

.content .list-menu li a:hover{
    background-color: #333333;
    border-bottom: 4px solid #FF4500;  
    color: #FF4500;
}

/* Primeira Seção */

.first-section{
    height: 100vh;
    width: 100vw;
    background-image: linear-gradient(rgba(29, 29, 29, 0.8), rgba(29, 29, 29, 0.8)), url(./img.fundopizza2.jpg);
    background-position: center center;
    background-size: cover;
    background-repeat: no-repeat;
    background-position-y: 50px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.first-section .conteudo-principal{
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;

}

.first-section h1{
    color:  #FF4500;
    font-size: 6rem;
    text-transform: uppercase;
    margin-bottom: 1rem;
    font-family: 'Indie Flower', cursive;
}

.first-section h2{
    color: rgb(177, 177, 177);
    font-size: 3rem;
    font-weight: 400;
    text-transform: uppercase;
    font-family: 'Indie Flower', cursive;
    margin-bottom: 3rem;
}

.btn button {
    width: 230px;
    height: 60px;
    cursor: pointer;
    text-transform: uppercase;
    background-color: #FF4500;
    border-radius: 10px;
    color: black;
    font-weight: 700;
    transition: all 400ms ease-in;
    margin-top: 5rem;
}

 .btn button:hover {
    border: 1px solid #FF4500;
    background-color: transparent;
    color: #FF4500;
}
.btn {
    width: 480px;
    display: flex;
    justify-content: space-between;
   
}


  /* sobre nós */
   
    .sobre-nos {
        height: 100vh;
    width: 100vw;
    background-image: linear-gradient(rgba(29, 29, 29, 0.8), rgba(29, 29, 29, 0.8)), url(./img.fundopizza2.jpg);
    background-position: center center;
    background-size: cover;
    background-repeat: no-repeat;
    background-position-y: 50px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    color: white;
    }
    
    .contentsobre {
        
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }
    
    .main{
        
        display: flex;
        justify-content: space-between;
    }
    
    .sobre-nos img {
        width: 400px;
    height: 400px;
    margin-top: 10rem;
    margin-left: 10rem;
    border: 2px solid rgb(155, 155, 155);
    }
    
    .contentsobre h2 {
       font-size: 6rem;
       margin-bottom: 1rem;
       font-family: 'Indie Flower', cursive;
    }
    
    .contentsobre p {
       text-align: center;
       font-size: 1.9rem;
       width: 600px;
    }

    /* Cardápio */
    .cardapio{
       width: 100vw;
       display: flex;
       flex-direction: column;
       align-items: center;
       justify-content: center;
       background-image: linear-gradient(rgba(29, 29, 29, 0.8), rgba(29, 29, 29, 0.8)), url(./img.fundopizza2.jpg);
    }

    .cardapio h2{
        font-size: 3rem;
        color: aliceblue;
        text-transform: uppercase;
        display: block
    }

 .itens-cardapio{
    
    width: 80%;
    margin-top: 2rem;
    margin-bottom: 2rem;
    display: grid;
    grid-template-columns:  repeat(auto-fit, minmax(300px,300px));
    justify-content: center;
    align-items: center;
    gap: 30px;
}

.itens-cardapio .info{
    background-color: rgba(221, 221, 221 );
    border: none;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 1.5rem;
}

.itens-cardapio img{
    width: 100%;
    height: 50px;
}

.itens-cardapio .info h3{
    font-size: 1.8rem;
    text-transform: uppercase;
    margin-bottom: 1rem;
    text-decoration: underline;
}

.itens-cardapio .info h4{
    font-size: 1.4rem;
   text-transform: uppercase;
   margin-bottom: 0.6rem;
   display: grid;
   justify-content: center;
   align-items: center;
 grid-template-columns: 150px 150px;  
 margin-left: 6rem;
}

.itens-cardapio .info h4 span{
    font-size: 1.6rem;
    color: #333333;
    margin-left: 1.5rem;
    text-decoration:underline;
    }
    
    .itens-cardapio div{
    background-color:#5e5252;
    box-shadow: 0px 0px 4px 1px;
    }
    .pedir-fomr{ 
        width: 200px;
       height: 35px;
       margin-top: 0.5rem;
       background-color: #FF4500;
       border-radius: 5px;
       text-transform: uppercase;
       cursor: pointer;
       color: black;
       transition: all 200ms ease-in;
    
    }
    .pedir-fomr:hover{
       background-color: #5e5252;
       color: white;
    }

.botao-voltar{
    width: 100px;
    height: 50px;
    margin-top: 0.5rem;
    background-color: #FF4500;
    border-radius: 5px;
    text-transform: uppercase;
    cursor: pointer;
    color: black;
    transition: all 200ms ease-in;
 
 }
.botao-voltar:hover{
    background-color: #4e4a4e;
    color:#FF4500;
 }


   /* Contatos */
.contatos{
    height: 100vh;
    width: 100vw;
    background-image: linear-gradient(rgba(29, 29, 29, 0.8), rgba(29, 29, 29, 0.8)), url(./img.fundopizza2.jpg);
    background-position: center center;
    background-size: cover;
    background-repeat: no-repeat;
    background-position-y: 50px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    background-color: #4e4a4e;
   font-size: 1.8rem;
   color: white;
 

}

.contatos h3{
    font-size: 6rem;
    margin-bottom: 3rem;
    font-family: 'GFS Didot', sans-serif;
    align-items: center;
}

.contatos-colocados{
    width: 650px;
    display: flex;
    justify-content: space-between;
    font-size: 2rem;
}

.contatos-colocados h2{
    border: none;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    padding: 1.5rem;
}

.contatos-colocados i{
    margin-right: 1rem;
    align-items: center;
}

.contatos-colocados div{
    cursor: pointer;
    transition: all 200ms ease-in;
}
.contatos-colocados:hover{
    color: #FF4500;
}

footer {
    height: 100px;
    background-color: #1f1e1f;
    color: #FF4500;
    font-size: 2rem;
    display: flex;
    align-items: center;
    justify-content: center;
}

.pedido-resgistramento{
    height: 100vh;
    width: 100vw;
    background-image: linear-gradient(rgba(29, 29, 29, 0.8), rgba(29, 29, 29, 0.8)), url(./img.fundopizza2.jpg);
    background-position: center center;
    background-size: cover;
    background-repeat: no-repeat;
    background-position-y: 50px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.pedido-resgistramento h1{
    font-size: 3rem;
    color: white;
}

.pedido-resgistramento h2{
    font-size: 2rem;
    color: white;
}


.instagram img{
    width: 400px;
    height: 400px;
    margin-top: 10rem;
    margin-left: 10rem;
    border: 2px solid rgb(155, 155, 155);
}

.instagram{
width:480px;
height: 500px;

}

.container-form{
    height: 100vh;
    width: 100vw;
    background-image: linear-gradient(rgba(29, 29, 29, 0.8), rgba(29, 29, 29, 0.8)), url(./img.fundopizza2.jpg);
    background-position: center center;
    background-size: cover;
    background-repeat: no-repeat;
    background-position-y: 50px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
}

.botao-Enviar{
    width: 150px;
    height: 35px;
    margin-top: 0.5rem;
    background-color: #FF4500;
    border-radius: 5px;
    text-transform: uppercase;
    cursor: pointer;
    color: black;
    transition: all 200ms ease-in;
 
}
.form-header h1{
    color:aliceblue;
    font-size: 4rem;
}

.form-header{
    margin-bottom: 3rem;
    display: flex;
    justify-content: space-between;
}
.login-button button{
    border: none;
    background-color: #FF4500;
    padding: 0.4rem 1rem;
    border-radius: 5px;
    cursor: pointer;
}

.login-button button:hover{
    background-color: #5e5252;
}

.login-button button a{
    text-decoration: none;
    font-weight: 500;
    color: aliceblue;
}

.input-group{
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
    padding: 1rem 0;
    
}

.input-box{
    display: flex;
    flex-direction: column;
    margin-bottom: 1.1rem;
}

.input-box input {
margin: 0.6rem 0;
padding: 0.8rem 1.2rem;
 border: none;
border-radius: 10px;
box-shadow: 1px 1px 6px #5e5252;
} 
        

.input-box input:hover{
    background-color: #FF4500;
}

.input-box input:focus-visible{
    outline: 1px solid #1f1e1f;
}

label{
color: aliceblue;
font-size: 1.5rem;
}

    .gender-title h3{
        color: aliceblue;
        font-size: 2rem;
    }
    

.gender-group {
  
  
    margin-top: 0.62rem;
    padding: 0 .5rem;
}

.gender-input {
    
   align-items: center;
}

.gender-input input {
    margin-right: 0.25rem;
}

.gender-input label {
    font-size: 1.6rem;
    font-weight: 400px;
    color: #FF4500;
}

.continue-button button {
    width: 100%;
    margin-top: 2.5rem;
    border: none;
    background-color: #FF4500;
    padding: 0.62rem;
    border-radius: 5px;
    cursor: pointer;
}

.continue-button button:hover {
    background-color: #FF4500;
}

.continue-button button a {
    text-decoration: none;
    font-size: 0.93rem;
    font-weight: 500;
    color: #fff;
}

.input-group{
    color:white;
    font-size: 1rem;
}



.buscar-box{
    width: 30px;
    height: 30px;
    background-color: #1f1e1f;
    overflow: hidden;
    display: flex;
    justify-content: space-between;
    position: relative;
    transition: .5s;
}

.buscar-box.ativar{
    width: 400px;
}

.buscar-box .lupa-buscar, .buscar-box .btn-fechar{
    min-width: 80px;
    height: 80px;
    display: flex;
    align-items: center;
    justify-content: center;
    cursor: pointer;
}

.buscar-box .btn-fechar i{
    font-size: 20px;
    margin-left: 15px;
    transition: all 200ms ease-in;
}

.buscar-box .btn-fechar i:hover{
    background-color: #4e4a4e;
    color: red;
}

.buscar-box .lupa-buscar i{
    font-size: 20px;
    transition: all 200ms ease-in;
}

.buscar-box .lupa-buscar i:hover{
    background-color: #FF4500;
}

.buscar-box .input-buscar{
    position: absolute;
    left: 80px;
    width: calc(100% - 120px);
    height: 100%;
    line-height: 40px;
    background-color: #1f1e1f;
    color: #FF4500;
}

.buscar-box .input-buscar input{
    border: 0;
    outline: 0;
    font-size: 20px;
    background-color: #1f1e1f;
    color: #FF4500;
}
