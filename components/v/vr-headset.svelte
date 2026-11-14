<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_12pfb5u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-sharp:vr-headset" {...props}></Icon>
<style>
:global(.d_12pfb5u) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.5 7h13a3 3 0 0 1 3 3v5a3 3 0 0 1-3 3h-3L14 15.5c-.6-.9-3.4-.9-4 0L8.5 18h-3a3 3 0 0 1-3-3v-5a3 3 0 0 1 3-3Z");
}

</style>
