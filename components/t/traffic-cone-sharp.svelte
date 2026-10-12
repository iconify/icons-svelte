<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vwen_2kdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:traffic-cone-sharp" {...props}></Icon>
<style>
:global(.vwen_2kdj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m10.25 3.75l.19-.736L11.2 3h1.6l.76.014l.19.736L17.65 18H6.35ZM3.75 18h16.5v3.25H3.75zm5-7.5h6.5m-7.5 4h8.5");
}

</style>
