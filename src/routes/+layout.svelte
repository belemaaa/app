<script lang="ts">
	// import '../app.css'
</script>

<div class="body">
	<nav>
		<ul>
			<li>
				<a href="/">Home</a>
			</li>
			<li>
				<a href="/posts">Posts</a>
			</li>
		</ul>
	</nav>

	<slot />
</div>

<style>
	.body {
		margin-left: 10px;
		margin-right: 10px;
	}
</style>
