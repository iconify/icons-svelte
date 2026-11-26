<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="priskdbml"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:sword-sharp" {...props}></Icon>
<style>
:global(.priskdbml) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4.7322 15.7322L15.9874 4.4771L21.0005 2.9995L19.5229 8.0126L8.2678 19.2678ZM2.7071 13.7071L3 14L10 21L10.2929 21.2929M6.5 17.5L3 21L2.7071 21.2929");
}

</style>
