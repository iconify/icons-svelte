<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvpj29bcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-turn-sharp-left" {...props}></Icon>
<style>
:global(.dvpj29bcp) {
  fill: currentColor;
  d: path("M6 6.83L4.41 8.41L3 7l4-4l4 4l-1.41 1.41L8 6.83V13h10v8h-2v-6H6z");
}

</style>
