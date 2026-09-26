<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="javbxgzww"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:send-sharp" {...props}></Icon>
<style>
:global(.javbxgzww) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M2 7.9174L22 2L16.0826 22L10.369 13.631L2 7.9174ZM10.369 13.631L22 2");
}

</style>
