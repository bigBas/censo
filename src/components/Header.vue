<template>
    <header id="iniLetter">
        <div class="container-fluid header-h">
            <div class="col-4 offset-1 d-inline-flex p-0 align-items-center">
                <a href="https://www.unam.mx/"
                    ><img
                        src="../img/Logo-UNAM.png"
                        class="img-fluid"
                        alt="Logo UNAM"
                /></a>
            </div>
            <div
                class="col-4  offset-2 d-inline-flex justify-content-end p-0 align-items-center"
            >
                <a href="http://www.acatlan.unam.mx/">
                    <img
                        src="../img/logo_fesa.png"
                        class="img-fluid"
                        alt="Logo Fes Acatlán"
                    />
                </a>
            </div>
        </div>

        <div
            class="container-fluid header-f d-flex justify-content-end align-items-center"
        >
            <!-- v-if="!['login'].includes($route.name)" va arriba, pero después 7u7-->
            <!-- <div
                class="mr-3"
            >
                <button
                    class="btn btn-danger m-0 px-3 py-2"
                >
                Cerrar Sesión
                </button>
            </div> -->
        </div>
    </header>
</template>
<script>
export default {
    data() {
        return {}
    },
    methods: {
        
    },
}
</script>
<style>
.header-h {
    /* background: #1b3d70; */
    background: #1b3d70;
    padding: 1rem 0;
}

.contenedor-header {
    padding: 1rem 0;
    display: flex;
    width: 100%;
    justify-content: space-between;
}

.contenedor-img {
    width: 40%;
    display: flex;
    align-items: center;
    justify-content: center;
}
.contenedor-img img {
    max-width: 100%;
}

.header-f {
    padding: 0.5rem 0;
    background-color: #bb8800;
}
#info {
    color: white;
}
.sesion {
    margin: 0.5rem;
    line-height: 0.5rem !important;
}
</style>
