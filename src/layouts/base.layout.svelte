
<script>
	export let title;
</script>

<html lang="en">
	<head>
		<meta charset="utf-8" />
		<meta name="viewport" content="width=device-width" />
		<title>{title}</title>
		<style global>
			@import "src/styles/global.css";
		</style>
	</head>
	<body>
		<slot/>
	</body>
</html>