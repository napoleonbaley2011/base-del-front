<template>
    <div class="body">

        <div class="wrapper">
            <form action="form-box login">
                <h1>INICIAR SESION</h1>

                <div class="input-box">
                    <input type="text" placeholder="Correo" required>
                    <i class='bx bxs-user'></i>

                </div>
                <div class="input-box">
                    <input type="password" placeholder="Password" required>
                    <i class='bx bxs-lock-alt'></i>
                </div>
                <div class="remember-forgot">
                    <label><input type="checkbox"> Recordar Usuario </label>
                </div>
                <button type="submit" class="btn">INGRESAR</button>


            </form>
        </div>
    </div>

</template>

<style>
.body {
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background-color: steelblue;
    background: url(../assets/img/login.jpg) no-repeat;
    background-size: cover;

}

.wrapper {
    position: relative;
    width: 400px;
    height: 520px;
    background: transparent;
    border: 2px solid rgba(255, 255, 255, .5);
    border-radius: 20px;
    backdrop-filter: blur(20px);
    box-shadow: 0 0 30px rgba(0, 0, 0, .5);
    display: flex;
    justify-content: center;
    align-items: center;
}

.wrapper h1 {
    font-size: 2em;
    color: #000;
    text-align: center;
    margin-bottom: 20px;
}

.input-box {
    position: relative;
    width: 100%;
    height: 50px;
    border-bottom: 2px solid #162938;
    margin: 30px 0;
}

input-box input:placeholder {
    color: #000;
}

.input-box label {
    position: absolute;
    top: 50%;
    left: 5px;
    transform: translateY(-50px);
    font-size: lem;
    color: #162938;
    font-weight: 500;
    pointer-events: none;
}

.input-box input {
    width: 100%;
    height: 100%;
    background: transparent;
    border: none;
    outline: none;
}

.input-box i {
    position: absolute;
    right: 10px;
    font-size: 1.5em;
    color: #000;
    line-height: 57px;
}

.remember-forgot {
    font-size: .9em;
    color: #000000;
    font-weight: 500;
    margin: 15px;
    display: flex;
}

.btn {
    width: 100%;
    height: 45px;
    background: #162938;
    border: none;
    outline: none;
    border-radius: 6px;
    cursor: pointer;
    font-size: 1.2em;
    color: #fff;
    font-weight: 500;
    margin-top: 20px;

}
</style>