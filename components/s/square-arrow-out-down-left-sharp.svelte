<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lywltebvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:square-arrow-out-down-left-sharp" {...props}></Icon>
<style>
:global(.lywltebvr) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 17L21 17L21 3L7 3L7 10M11.2929 12.7071L3.1464 20.8536M12 21L3 21L3 12");
}

</style>
