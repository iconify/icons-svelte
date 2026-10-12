<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yz36sfr7b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:spike-strip-sharp" {...props}></Icon>
<style>
:global(.yz36sfr7b) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.64 14.52l1.32-4.54l.14-.48l.14.48l1.32 4.54l.14.48l.14-.48l1.32-4.54l.14-.48l.14.48l1.32 4.54l.14.48l.14-.48l1.32-4.54l.14-.48l.14.48l1.32 4.54l.14.48l.14-.48l1.32-4.54l.14-.48l.14.48l1.32 4.54l.14.48l.14-.48l1.32-4.54l.14-.48l.14.48l1.32 4.54l.14.48h-16zm-.89.48h18.5v4.5H2.75z");
}

</style>
