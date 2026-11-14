<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e_pp5abkg"/><path class="n7fy89bnu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:sports-tv" {...props}></Icon>
<style>
:global(.e_pp5abkg) {
  d: path("M2.5 4h19v13.5h-19ZM7 17.5l-1.5 3m11.5-3l1.5 3M12 4v13.5");
}

:global(.n7fy89bnu) {
  d: path("M9.25 10.75a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Z");
}

:global(.ulnmmdpxh) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
