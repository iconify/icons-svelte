<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z80bkzg0b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:topic-sharp" {...props}></Icon>
<style>
:global(.z80bkzg0b) {
  fill: currentColor;
  d: path("M2 20V4h8l2 2h10v14zm4-4h8v-2H6zm0-4h12v-2H6z");
}

</style>
