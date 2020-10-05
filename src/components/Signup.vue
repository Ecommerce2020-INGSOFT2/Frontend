<template>
    <div class="vue-tempalte">
        <form>
            <h3>Registrate</h3>

            <div class="form-group">
                <label>Nombre Completo</label>
                <input type="text" class="form-control form-control-lg"/>
            </div>

            <div class="form-group">
                <label>Correo Electronico</label>
                <input type="email" class="form-control form-control-lg" />
            </div>

            <div class="form-group">
                <label>Password</label>
                <input type="password" class="form-control form-control-lg" />
            </div>

            <button type="submit" class="btn btn-dark btn-lg btn-block">Sign Up</button>

            <p class="forgot-password text-right">
                Todavia no estas registrado?
                <router-link :to="{name: 'login'}">Ingresa aqui.</router-link>
            </p>
        </form>
    </div>
</template>

<script>
    export default {
        data() {
            return {}
        }
    }
</script>