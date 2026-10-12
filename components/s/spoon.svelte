<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bw7k9ncbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:spoon" {...props}></Icon>
<style>
:global(.bw7k9ncbi) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11.61 12.39a5.5 3.75-45 0 1 7.78-7.78a5.5 3.75-45 0 1-7.78 7.78m-.36.36L4 20");
}

</style>
