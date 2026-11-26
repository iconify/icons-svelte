<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="duwujibkb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:zodiac-sagittarius-sharp" {...props}></Icon>
<style>
:global(.duwujibkb) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 3L21 3L21 10M2.7071 21.2929L20.8243 3.1757M4.7071 12.7071L11.2929 19.2929");
}

</style>
