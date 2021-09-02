<template>
    <main id="register">
        <h1>
        ¿QUIERES COMPRAR?<br>
        ¡REGÍSTRATE!
    </h1>
    <p>Para disfrutar de nuestros prouctos debe llenar el formulario de registro!</p>
    <form>

    <div class="form-item">
        <label for="">NOMBRE DE USUARIO*</label>
        <input type="text">
    </div>

    <div class="form-item">
        <label for="">DIRECCIÓN*</label>
        <input type="text">
    </div>

    <div class="form-item">
        <label for="">TELÉFONO*</label>
        <input type="tel">
    </div>

    <div class="form-item">
        <label for="">CORREO*</label>
        <input type="email">
    </div>

    <div class="form-item">
        <label for="">CONTRASEÑA*</label>
        <input type="password">
    </div>

    <div class="form-item">
        <label for="">REPETIR CONTRASEÑA*</label>
        <input type="password">
    </div>
        
    <button type="submit">REGISTER</button>

    </form>
    </main>
</template>

<style>
    #register form {
        display: flex;
        flex-wrap: wrap;
        justify-content: space-between;
        width: 75%;
        margin: 0 auto;
        padding: 3rem 0;
    }
    #register .form-item {
        display: flex;
        flex-direction: column;
        justify-content: left;
        width: 49%;
        margin-bottom: 1rem;
    }
    #register button {
        margin: auto;
    }
</style>