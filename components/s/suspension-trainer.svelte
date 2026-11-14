<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mervg3bjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:suspension-trainer" {...props}></Icon>
<style>
:global(.mervg3bjt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.5V8m0 3l-5 6m5-6l5 6m-6.5-9h3v3h-3Zm-6 9h5v3.5h-5Zm10 0h5v3.5h-5Z");
}

</style>
