<script>
    export let name;
    import '../resources/styles.css';
</script>

<main>
    <!-- <img src="./svelte-climasha\src\Icon awesome-sun.png/" alt=""> -->

    <!-- <h1>¡App {name}!</h1> -->
    <div class="izquierda">
        <div id="search" class="Rectangle-5 Search">
            <input id="busqueda" type="button-search" placeholder="Buscar" />
            <img src="img/lupita1.png" alt="Buscar" />
        </div>

        <div id="pais" class="pais">
            <img src="img/casita.png" />
            <p class="texto">País</p>
        </div>
        <div id="ciudad" class="pais">
            <img src="img/ciudad.png" />
            <p class="texto">Ciudad</p>
        </div>
    </div>
    <div class= "derecha">
        <img src="img/solecito.png" class="sol"/>
        <p class="texto">7 : 50 am</p>
        <p class="texto">Bogotá</p>
        <p class="texto">22 - mar - 2021</p>
    </div>
</main>

<style>
    main {
        text-align: center;
        vertical-align: top;
        width: 100%;
        margin: 0px auto;
        border-radius: 2.5rem;
        display: flex;
    }
    input {
        border: 0px;
    }

    h1 {
        color: #07a188;
        text-transform: uppercase;
        text-align: center;
        font-size: 4em;
        font-weight: 100;
    }
    .izquierda{
        display: inline-flex;
        flex-direction: column;
        padding-left: 30px;
    }

    .derecha {
        display: inline-flex;
        flex-direction: column;
        text-align: center;
        width: 50%;
        justify-content: center;
        align-items: center;

    }

    .texto{
        text-align: center;

    }
    .sol{
        height: 100px;
        width: 100px;
        text-align: right;
    }
</style>
