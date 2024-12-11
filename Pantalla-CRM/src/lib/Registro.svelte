<form>
        <label for="">Nombre de usuario</label>
        <input type="text" placeholder="Nombre de usuario" />
        <label for="">Email</label>
        <input type="email" placeholder="Email" />
        <label for="">Constraseña</label>
        <input type="password" placeholder="Contraseña" />
    <button type="button">Iniciar sesión</button>
</form>

<style>
    form {
        margin-top: 10%;
        display: flex;
        flex-direction: column;
        gap: 10px;
        align-items: center;
        width: 80%;
        height: 100%;
        background-color: #FF3B30;
    }

    label {
        color: white;
        text-align: left;
        width: 70%;
    }

    input {
        padding: 10px;
        border-radius: 5px;
        border: none;
        width: 70%;
    }

    button {
        background-color: black;
        color: white;
        border: none;
        padding: 10px;
        border-radius: 25px;
        cursor: pointer;
        width: 40%;
        margin-top: 25%;
        margin-bottom: 25%;
    }

    button:hover {
        background-color: #333;
    }
</style>