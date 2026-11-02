<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cmqyipb7c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:sparkle-duocolor-sharp" {...props}></Icon>
<style>
:global(.cmqyipb7c) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 3c0 4 5 9 9 9c-4 0-9 5-9 9c0-4-5-9-9-9c4 0 9-5 9-9");
}

</style>
