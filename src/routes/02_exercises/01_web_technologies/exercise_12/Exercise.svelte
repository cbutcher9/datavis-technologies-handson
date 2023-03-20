<script>
	let clicked = false;
</script>

<div>
	<button class="btn btn-primary" on:click={() => (clicked = true)}>
		click here
	</button>
	<!--  -->
</div>

{#if clicked = true}
	<p> <i>You have clicked the button!</i> </p>
{:else}
	<p> <i>You have to click the button!</i> </p>
{/if}
