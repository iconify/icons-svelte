<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-gfh_fab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:tongs-sharp" {...props}></Icon>
<style>
:global(.c-gfh_fab) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10 4.75v-2h4v2m-4 0l-4 13.5l2.25 2.5m5.75-16l4 13.5l-2.25 2.5");
}

</style>
