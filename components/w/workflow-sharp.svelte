<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qrg4yrmcl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:workflow-sharp" {...props}></Icon>
<style>
:global(.qrg4yrmcl) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 4L11 4L11 10L3 10L3 4ZM13 14L21 14L21 20L13 20L13 14ZM7 10L7 17L13 17");
}

</style>
