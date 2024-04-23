<script>
	import { parse } from 'csv-parse/browser/esm/sync';
	const csv = parse(`"a","b"\n"1","2"`, {
		columns: true,
		delimiter: ','
	});
	console.log(csv);
</script>

<pre>{JSON.stringify(csv, null, 2)}</pre>
