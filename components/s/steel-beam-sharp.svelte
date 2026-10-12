<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j6onhwrxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:steel-beam-sharp" {...props}></Icon>
<style>
:global(.j6onhwrxt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13.25h18.5v5H2.75zm2 2.5h14.5M12 3v4.5m0 0l-6.5 5.75M12 7.5l6.5 5.75");
}

</style>
