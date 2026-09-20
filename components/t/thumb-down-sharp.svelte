<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s4d7iwbmc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:thumb-down-sharp" {...props}></Icon>
<style>
:global(.s4d7iwbmc) {
  fill: currentColor;
  d: path("M1 16v-4.4L4.65 3H16v13l-7 7l-1.85-1.85L8.45 16zm17 0V3h4v13z");
}

</style>
