<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t4dm92bnl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:wb-twilight-2-rounded" {...props}></Icon>
<style>
:global(.t4dm92bnl) {
  fill: currentColor;
  d: path("M3 20q-.425 0-.712-.288T2 19t.288-.712T3 18h18q.425 0 .713.288T22 19t-.288.713T21 20zm2-4q0-2.925 2.038-4.962T12 9t4.963 2.038T19 16z");
}

</style>
