<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n3-y9xb8l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix:triangle" {...props}></Icon>
<style>
:global(.n3-y9xb8l) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.27 7.91l4.44 7.647a2.625 2.625 0 0 1-2.27 3.943H7.56a2.625 2.625 0 0 1-2.27-3.943L9.73 7.91a2.625 2.625 0 0 1 4.54 0");
}

</style>
