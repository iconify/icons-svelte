<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j3wrfib0i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:skip-forward-fill-sharp" {...props}></Icon>
<style>
:global(.j3wrfib0i) {
  fill: currentColor;
  d: path("m4.504 4.136l12 7a1 1 0 0 1 0 1.728l-12 7A1.002 1.002 0 0 1 3 19V5a.998.998 0 0 1 1.504-.864M21 19a1 1 0 0 1-2 0V5a1 1 0 0 1 2 0Z");
}

</style>
