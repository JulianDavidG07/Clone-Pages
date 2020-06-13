<template>

    <nav 
         class="flex justify-between px-16 fixed bottom-0 w-full bg-white border-t-2 border-gray-200 px-20 py-2">
    
        <!-- logo navbar -->
        <div>
          <div class="flex justify-center p-1">
              <img src="../assets/logo.png" style="height: 25px;">
          </div>
          <div class="block text-2xs" style="color:red;">Explora</div>
        </div>
    
        <!-- heart logo -->
        <div class="text-gray-800">
          <div class="flex justify-center p-1">
              <ion-icon name="heart-outline" style="font-size: 27px;"/>
          </div>
          <div class="block text-2xs">Guardado</div>
        </div>
    
        <!-- logo user -->
        <div class="text-gray-800">
          <div class="flex justify-center p-1">
              <ion-icon name="person-circle-outline" style="font-size: 27px;"/>
          </div>
          <div class="block text-2xs">Iniciar Sesión</div>
        </div>
      
    </nav>  

</template>

<script>
export default {
  name: 'Navbar',

}
</script>

