<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lbbrn5bnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoven:warm-front" {...props}></Icon>
<style>
:global(.lbbrn5bnw) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m3.5 20.5l1.97-1.97m3.54-3.54l1.22-1.22m3.54-3.54l1.22-1.22m3.54-3.54L20.5 3.5M5.47 18.53a2.5 2.5 0 0 1 3.54-3.54Zm4.76-4.76a2.5 2.5 0 0 1 3.54-3.54Zm4.76-4.76a2.5 2.5 0 0 1 3.54-3.54Z");
}

</style>
