<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vii51dbms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:stairs" {...props}></Icon>
<style>
:global(.vii51dbms) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 21.25a1 1 0 0 1-1-1v-3H7.5v-4.5h4.75v-4.5H17v-4.5h3.25a1 1 0 0 1 1 1v15.5a1 1 0 0 1-1 1Zm-1-7.5L13.5 3.5");
}

</style>
