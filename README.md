# Formulario-de-Contacto-com-HTML-CSS-e-Bootstrap


<!DOCTYPE html>
<html lang="en">
<head>
   <meta charset="UTF-8">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <title>Formulario de Contacto com html, css e bootstrap</title>

  <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous">
   

 <style>
   
     body{

          background-color: #ffffff;
          align-items: center;
          justify-content: center;
          padding: 30px;
          height: 100vh;


     }

    .form-conteiner{

        margin:auto;
        max-width: 600px;
        padding: 30px;
        border-radius: 8px;
        background-color: rgba(15, 200, 150, 0.801); 
        box-shadow: 0px 0px 10px 0px rgba(0,0,0,0.1);

    }


 </style>


</head>



<body>
<div class="conteiner">

   <div class="form-conteiner">
     
   <h2> Formulario de Contacto</h2>

         <form action="#"  method="POST">

            <div class="form-group">
               <label for="Usuario" >Usuario</label>
               <input type="text" class="form-control" placeholder="Digite o usuario">
                
            </div>
            
            <div class="form-group">
               <label for="Email" >Email</label>
               <input type="email" class="form-control" placeholder="Digite o email">
                
            </div>

            <div class="form-group">
               <label for="Data" >Data de Nascimento</label>
               <input type="date" class="form-control" placeholder="Digite a data de nascimento">
                
            </div>
            
            <div class="form-group">
               <label for="coment" >Comentario</label>
              <textarea name="caixa" class="form-control" rows="5" required></textarea>
                
            </div>


            <button class="btn btn-primary"> Enviar </button>
            <a href="ocam.exe" class="btn btn-danger" download>Download</a>




         </form>   
      </div>
   </div>



</div>
             








              </form>


   
</body>
</html>
