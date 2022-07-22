<script context="module">
		export function load({ error }) {
		return {
			props: { message: error.message }
		};
	}
</script>

<script>
	export let message
</script>

<div class="error">
  <h2>Ooops</h2>
  <p>{message}</p>
  <a href="/guides">View all Guides...</a>
</div>
<style>
  .error {
    text-align: center;
    margin-bottom: 60px;
    background: rgb(21, 3, 49);
    color: crimson;
    border-radius: 20px;
    border: 2px solid crimson;
    padding: 20px;
  }
</style>


