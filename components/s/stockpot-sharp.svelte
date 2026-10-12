<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v7yhiobfu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:stockpot-sharp" {...props}></Icon>
<style>
:global(.v7yhiobfu) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5.75v-2m-6.25 4.5a6.25 2.5 0 0 1 12.5 0Zm.5 2.5h11.5v10.5H6.25zm0 2.75h-2.5m14 0h2.5");
}

</style>
