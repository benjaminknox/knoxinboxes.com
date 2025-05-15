<script lang="ts">
  import 'reset-css/reset.css';
	import '@awenovations/aura/dist/tokens/_variables.css';
  import KnoxInBoxes from "$lib/assets/KnoxInBoxes.png";

</script>


<svelte:head>
  <title>Knox In Boxes</title>

  <script data-name="BMC-Widget" data-cfasync="false" src="https://cdnjs.buymeacoffee.com/1.0.0/widget.prod.min.js" data-id="benjaminknox" data-description="Support me on Buy me a coffee!" data-message="" data-color="#FF813F" data-position="Right" data-x_margin="18" data-y_margin="18"></script>
</svelte:head>

<img src={KnoxInBoxes} alt="" />

<style lang="scss">
	@import url('https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,100;0,200;0,300;0,400;0,500;0,600;0,700;0,800;0,900;1,100;1,200;1,300;1,400;1,500;1,600;1,700;1,800;1,900&display=swap');

  :global(html, body) {
		background: var(--aura-background);
		font: var(--aura-default-regular);
		color: var(--aura-font-color);
		height: 100%;
		width: 100%;
    text-align: center;
	}

  img {
    width: 60vw;
    margin-top: 8vh;
  }

</style>
