<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d9v5enbdg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:spacing-vertical" {...props}></Icon>
<style>
:global(.d9v5enbdg) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6.5v11M9.5 9L12 6.5L14.5 9m-5 6l2.5 2.5l2.5-2.5M3 3h18M3 21h18");
}

</style>
