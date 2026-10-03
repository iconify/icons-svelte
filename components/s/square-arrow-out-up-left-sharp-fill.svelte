<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nov4-jb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-arrow-out-up-left-sharp-fill" {...props}></Icon>
<style>
:global(.nov4-jb9h) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 7L21 7L21 21L7 21L7 14M11.2929 11.2929L3.1464 3.1464M12 3L3 3L3 12");
}

</style>
