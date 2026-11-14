<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jnj3e4btk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tarp-diamond" {...props}></Icon>
<style>
:global(.jnj3e4btk) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12 5l7 7l-7 7l-7-7Zm0 7h.01M12 2.25h.01M21.75 12h.01M12 21.75h.01M2.25 12h.01");
}

</style>
