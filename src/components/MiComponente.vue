<template>
    

    <div class="hello">
        <H1>Compra y venta de partes</H1>

        <label for="nombre">Primer nombre:</label> <br> <br>
        <input type="text" class="nombre" id="nombre" name="nombre" placeholder="Ingrese su nombre aqui">
        
    </div>

    
    
</template>

<script>
export default {
    name: "MiComponente"
}
</script>

<style scoped>

.hello {
    background-color: aqua;
    margin: 50px 0 0;
    height: 1000px;
}

.nombre {
   border-radius: 5px;
   border: 1px solid #39c;
   width: 500px;
   height: 30px;
   text-align: center;
   font-size: 28px;


}

</style>