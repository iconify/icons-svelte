<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dy5ymfapz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:summarize-ai-sharp" {...props}></Icon>
<style>
:global(.dy5ymfapz) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.25 3.75h17.5M3.25 8h17.5m-17.5 4.25h17.5m-12 3L12 18l3.25-2.75m-7 5.75h7.5");
}

</style>
