<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lady6yb7y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:up-next-sharp" {...props}></Icon>
<style>
:global(.lady6yb7y) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 4.75h16.5m-16.5 5h16.5m-8 7.5h8M4.59 14.54l3.32 2.17l.84.54l-.84.54l-3.32 2.17l-.84.54V14z");
}

</style>
