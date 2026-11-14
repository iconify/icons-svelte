<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uyqj_ye7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:salt-dishwasher" {...props}></Icon>
<style>
:global(.uyqj_ye7e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.3 21.5H4v-13h12v4M5 3h10v5.5H5Zm13.5 10.75l2.75 4a3 3 0 1 1-5.5 0Z");
}

</style>
