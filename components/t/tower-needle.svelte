<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d6w2j-pkw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:tower-needle" {...props}></Icon>
<style>
:global(.d6w2j-pkw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 21V9M8 21l4-9l4 9M7.5 8a4.5 2 0 1 0 9 0a4.5 2 0 1 0-9 0ZM12 6V3");
}

</style>
