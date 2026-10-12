<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lkfv57sra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:windsock-sharp" {...props}></Icon>
<style>
:global(.lkfv57sra) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 21.25V2.75m0 1l15 2l1 .13v3.24l-1 .13l-15 2Zm5 .75v6m5-5.25v4.5");
}

</style>
