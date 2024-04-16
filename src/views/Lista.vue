<template>  
<div class="body1">

    <nav>
        <ul>
            <li><a href="inicio.vue">Inicio</a><i class="bi bi-envelope"></i></li>
            <li><a href="documentos.vue">Documentos</a></li>
            <li><a href="seguimiento.vue">Seguimiento</a></li>
            <li><a href="configuraciones.vue">Configuraciones</a></li>
        </ul>
    </nav>
    
        <h1>PLANEAR</h1>
        <table class="tabla-opciones">
            <tbody>
                <tr>
                    <td>Analisis FODA</td>
                    <td>
                        <button class="btn-abrir-formulario">Abrir formulario</button>
                    </td>
                </tr>
                <tr>
                    <td>Mapa de Procesos</td>
                    <td>
                        <button class="btn-abrir-formulario">Abrir formulario</button>
                    </td>
                </tr>
                <tr>
                    <td>Matriz de partes interesadas</td>
                    <td>
                        <button class="btn-abrir-formulario">Abrir formulario</button>
                    </td>
                </tr>
                <tr>
                    <td>Alcance</td>
                    <td>
                        <button class="btn-abrir-formulario">Abrir formulario</button>
                    </td>
                </tr>
                <tr>
                    <td>Politica</td>
                    <td>
                        <button class="btn-abrir-formulario">Abrir formulario</button>
                    </td>
                </tr>
                <tr>
                    <td>Evidencia de liderazgo y compromiso</td>
                    <td>
                        <button class="btn-abrir-formulario">Abrir formulario</button>
                    </td>
                </tr>
                <tr>
                    <td>Matriz de riesgos y oportunidades</td>
                    <td>
                        <button class="btn-abrir-formulario">Abrir formulario</button>
                    </td>
                </tr>
                <tr>
                    <td>Roles y responsabilidades</td>
                    <td>
                        <button class="btn-abrir-formulario">Abrir formulario</button>
                    </td>
                </tr>
                <tr>
                    <td>Matriz IPER</td>
                    <td>
                        <button class="btn-abrir-formulario">Abrir formulario</button>
                    </td>
                </tr>
                <tr>
                    <td>Matriz de requisitos legales</td>
                    <td>
                        <button class="btn-abrir-formulario">Abrir formulario</button>
                    </td>
                </tr>
                <tr>
                    <td>Planificacion de objetivos</td>
                    <td>
                        <button class="btn-abrir-formulario">Abrir formulario</button>
                    </td>
                </tr>
            </tbody>
        </table>
</div>
      

</template>
<style>
    @import url('https://fonts.googleapis.com/css?family=Montserrat&display=swap');
.body1{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Montserrat', sans-serif;
}
.tabla-opciones {
    width: 100%;
    border-collapse: collapse;
}

.tabla-opciones th,
.tabla-opciones td {
    border: 1px solid #ddd;
    padding: 8px;
    text-align: left;
}

.tabla-opciones i {
    margin-right: 5px;
}


</style>