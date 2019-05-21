<script>
	let count = 0;

	function handleIncrement() {
	  count += 1;
	}
	function handleDecrement() {
	  count -= 1;
	}
</script>

<style>
	button {
	  background: #ff3e00;
	  color: white;
	  border: none;
	  padding: 8px 12px;
	  border-radius: 2px;
	  font-size: 24px;
	}
</style>

<p>{count}</p>

<button on:click={handleIncrement}>+</button>
<button on:click={handleDecrement}>-</button>