<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i65ntbc5a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:view-day" {...props}></Icon>
<style>
:global(.i65ntbc5a) {
  fill: currentColor;
  d: path("M4 18.77v-1h16v1zM4 6.23v-1h16v1zM5.616 15q-.691 0-1.153-.462T4 13.385v-2.77q0-.69.463-1.152T5.616 9h12.769q.69 0 1.153.463T20 10.616v2.769q0 .69-.462 1.153T18.384 15z");
}

</style>
