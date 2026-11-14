<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l6fn0lb6l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:scripture-book-open" {...props}></Icon>
<style>
:global(.l6fn0lb6l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6c-2-1.5-5.5-2-9-1.5V19c3.5-.5 7 0 9 1.5M12 6c2-1.5 5.5-2 9-1.5V19c-3.5-.5-7 0-9 1.5M12 6v14.5");
}

</style>
