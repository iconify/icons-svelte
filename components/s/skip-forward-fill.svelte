<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gz3r3tbmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:skip-forward-fill" {...props}></Icon>
<style>
:global(.gz3r3tbmb) {
  fill: currentColor;
  d: path("m7.59 4.456l8 5a3 3 0 0 1 0 5.088l-8 5A2.999 2.999 0 0 1 3 17V7a3 3 0 0 1 4.59-2.544M19 19V5a1 1 0 0 1 2 0v14a1 1 0 0 1-2 0");
}

</style>
