<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zvh22zbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:signal-cellular-pause-rounded" {...props}></Icon>
<style>
:global(.zvh22zbmc) {
  fill: currentColor;
  d: path("M3.7 20.3L20.3 3.7q.475-.475 1.088-.213t.612.938V12q0 .425-.288.713T21 13h-5q-1.25 0-2.125.875T13 16v5q0 .425-.288.713T12 22H4.425q-.675 0-.937-.612T3.7 20.3M19 21v-5q0-.425.288-.712T20 15t.713.288T21 16v5q0 .425-.288.713T20 22t-.712-.288T19 21m-4 0v-5q0-.425.288-.712T16 15t.713.288T17 16v5q0 .425-.288.713T16 22t-.712-.288T15 21");
}

</style>
