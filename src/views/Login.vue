<template>
    <div class="Login" >
        <div class="container" >
    
      <form method="POST" action="#" >
            
    <h3 class="text-center" >Login</h3>                   
     <input type="text" class="form-control mt-2" maxlength="10" name="username" placeholder="username" required> 
     <input type="password" class="form-control mt-2" maxlength="10" name="password" placeholder="password" required>     
  <button type="submit"  class="btn btn-primary form-control mt-3" name="submit">Login</button> 
                 
        </form>
        

      </div>
   </div>
  
  </template>

  
  <style>
body{
    font-family: 'Sarabun', sans-serif;
    background-color: #efefef;
}
/*css แบบ class จะขึ้นต้นด้วย .    */
/*css แบบ id จะขึ้นต้นด้วย #   */
.Login{
    /* top bottom left right */
    /*margin: 0px auto;*/ 
    margin: 50px auto; 
    padding: 30px;
    border: 10px solid #f5f5f5;
    background: white;
    border-radius: 10px 10px 10px 10px;
    /* width: 100%; */
    max-width: 380px;
}
</style>