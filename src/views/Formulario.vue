<template>
    <div>
        <h2>Formulario de Contacto</h2>
        <form>
            <div>
                <label for="nombre">Nombre:</label><br>
                <input type="text" id="nombre" name="nombre">
            </div>
            <br>
            
            <div>
                <label for="email">Email:</label><br>
                <input type="email" id="email" name="email">
            </div>
            <br>
            
            <div>
                <label for="mensaje">Mensaje:</label><br>
                <textarea id="mensaje" name="mensaje" rows="4"></textarea>
            </div>
            <br>
            
            <button type="submit">Enviar</button>
        </form>
    </div>
</template>

<script>
    export default { 
        name: 'Formulario', 
    } 
</script>

<style>
    
</style>