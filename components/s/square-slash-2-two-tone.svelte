<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k9tlu577m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-slash-2-two-tone" {...props}></Icon>
<style>
:global(.k9tlu577m) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 4L17 4C18.6569 4 20 5.3431 20 7L20 17C20 18.6569 18.6569 20 17 20L7 20C5.3431 20 4 18.6569 4 17L4 7C4 5.3431 5.3431 4 7 4ZM3 21L21 3");
}

</style>
