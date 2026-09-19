<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kdp-zedij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-turn-sharp-right" {...props}></Icon>
<style>
:global(.kdp-zedij) {
  fill: currentColor;
  d: path("m18 6.83l1.59 1.58L21 7l-4-4l-4 4l1.41 1.41L16 6.83V13H6v8h2v-6h10z");
}

</style>
