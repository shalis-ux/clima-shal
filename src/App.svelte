<script>
	export let name;
    import '../resources/styles.css';
</script>

<main>
    <!-- <img src="./svelte-climasha\src\Icon awesome-sun.png/" alt=""> -->
	<h1>¡App {name}!</h1>
    <div id="search">
        <div>
            <input id="busqueda" class="Rectangle-5 Search " type="button-search">
        </div>
        <div>
            <img src="img/Icon awesome-search.png" alt="">
        </div>
    </div>
    <div id="pais" class="pais">
        País
    </div>
    <div id="ciudad" class="ciudad">
        ciudad
        <!-- <img src="Icon awesome-search.png" class="Icon-material-location-city"> -->
    </div>
	<p>7 : 50 am </p>
	<p>Bogotá </p>
	<p>22 - mar - 2021</p>
</main>

<style>
	main {
		text-align: center;
		padding: 1em;
		width: 100%;
		margin: 0px auto;
        border-radius: 2.5rem;
	}


	h1 {
		color: #07a188;
		text-transform: uppercase;
		font-size: 4em;
		font-weight: 100;
	}

	@media (min-width: 640px) {
		main {
			max-width: none;
		}
	}

</style>
