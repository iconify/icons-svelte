<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xz76q5bpc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:transit-enterexit-outline-sharp" {...props}></Icon>
<style>
:global(.xz76q5bpc) {
  fill: currentColor;
  d: path("M6 18V8h3v4.75l6.8-6.8l2.2 2.2L11.15 15H16v3z");
}

</style>
