<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iagyj3bnx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sports-bra" {...props}></Icon>
<style>
:global(.iagyj3bnx) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 3.5H9C9 8 10.25 10 12 10s3-2 3-6.5h3.5v6c0 2 1.5 3.5 1.5 5.5v5.5H4V15c0-2 1.5-3.5 1.5-5.5ZM4 17h16");
}

</style>
