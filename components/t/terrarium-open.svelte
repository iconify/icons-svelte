<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yff6xggkj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:terrarium-open" {...props}></Icon>
<style>
:global(.yff6xggkj) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 10c0 7 4 11.5 9 11.5S21 17 21 10m-9 8.75V7.5M12 9c0-3-2-5-5.5-5C6.5 7 9 9 12 9Zm0-1.5c0-3 2-5 5.5-5c0 3-2.5 5-5.5 5Z");
}

</style>
