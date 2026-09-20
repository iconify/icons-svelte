<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c24gsgbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:stop-sharp" {...props}></Icon>
<style>
:global(.c24gsgbav) {
  fill: currentColor;
  d: path("M7 17V7h10v10z");
}

</style>
