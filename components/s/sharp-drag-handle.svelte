<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="woje_d01k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-drag-handle" {...props}></Icon>
<style>
:global(.woje_d01k) {
  fill: currentColor;
  d: path("M20 9H4v2h16zM4 15h16v-2H4z");
}

</style>
