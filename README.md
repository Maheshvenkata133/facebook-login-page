# facebook-login-page
*{
     margin: 0;
     padding: 0;
     box-sizing: border-box;
     font-family: Helvetica, Arial, sans-serif;
}
body{
     width: 100vw;
     background-color: #f0f2f5;
}
.form-container{
     width: 100%;
     display: flex;
     flex-direction: column;
     justify-content: center;
     align-items: center;
     gap: 1rem;
     height: 100vh;
}
form{
     background-color: #ffffff;
     padding: 1rem;
     display: flex;
     flex-direction: column;
     justify-content: center;
     align-items: center;
     box-shadow: 0 2px 4px rgb(0 0 0 / 10%), 0 8px 16px rgb(0 0 0 / 10%);
     gap: 1rem;
     border-radius: 10px;
}
.form-container h1{
     color: #1877f2;
     text-transform: lowercase;
}
.input{
     height: 50px;
     width: 350px;
     font-size: 17px;
     border-radius: 6px;
     font-family: Helvetica, Arial, sans-serif;
}
input[type="text"]{
     width: 100%;
     height: 100%;
     color: #1d2129;
     padding-left: 1rem;
     border-radius: 6px;
     font-size: 17px;
     border: 1px solid #dddfe2;
     outline: none;
}
input{
     border: 1px solid #dddfe2;
}
input:focus{
     border: 1px solid #1877f2;
}
.password-container{
     display: flex;
     justify-content: center;
     align-items: center;
}
.password-container{
     border: 1px solid #dddfe2;
}
.fa{
     margin-left: .5rem;
}
input[type="password"]{
     width: 80%;
     border-radius: 6px;
     font-size: 17px;
     border: none;
     outline: none;
     color: #1d2129;
}
input[type="submit"]{
     width: 100%;
     height: 100%;
     background: #1877f2;
     border-radius: 6px;
     color: #fff;
     font-size: 20px;
     font-weight: bold;
     cursor: pointer;
}
.forgot-password-container{
     text-align: center;
     border-bottom: 1px solid #dddfe2;
}
.forgot-password-container a{
     text-decoration: none;
     color: #1877f2;
}
.create-new{
     background-color: #36a420;
     color: #fff;
     font-weight: bolder;
     outline: none;
     border: none;
     padding: 0rem 1rem;
     width: auto;
     cursor: pointer;
}
p{
     margin-top: 1rem;
}
footer{
     width: 100%;
     background-color: #ffffff;
}
.wrapper{
     width: 70%;
     margin: 0rem auto;
     margin-bottom: 0;
     color: #666870;
     font-size: 10px;
}
footer label{
     cursor: pointer;
}
.language-section button{
     width: 20px;
     height: 20px;
}
.language-section{
     display: grid;
     padding: 2rem 0px;
     grid-template-columns: repeat(auto-fit,min(60px));
}
.navigation{
     padding: 1rem 0;
     display: grid;
     border-top: 1px solid #dddfe2;;
     grid-template-columns: repeat(auto-fit, min(100px));
}
