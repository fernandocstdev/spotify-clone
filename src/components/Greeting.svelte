<script lang="ts">
	const currentTime = new Date();
	const currentHour = currentTime.getHours();

	let greeting = "";

	if (currentHour < 12) greeting = "Buenos días";
	else if (currentHour < 18) greeting = "Buenas tardes";
	else greeting = "Buenas noches";
</script>

<h1 class="text-2xl font-bold text-zinc-200">{greeting}</h1>
