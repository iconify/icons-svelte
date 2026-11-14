<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2ag0_bnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:wind-turbine-offshore" {...props}></Icon>
<style>
:global(.d2ag0_bnm) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 8.5v-6m0 6l5.5 3.25M12 8.5l-5.5 3.25M12 8.5v12m-9.5 0q2.375-2 4.75 0t4.75 0t4.75 0t4.75 0");
}

</style>
