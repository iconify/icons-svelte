<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="te12uqykr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:trademark-sign-sharp" {...props}></Icon>
<style>
:global(.te12uqykr) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 13h9m-9 5h12M12.5 4.5H16m-1.75 0v5m3 0v-5L19 6.75l1.75-2.25v5");
}

</style>
