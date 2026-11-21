<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xko17acls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:type-width-sharp-fill" {...props}></Icon>
<style>
:global(.xko17acls) {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 6L4 5L4 2L20 2L20 5L20 6M12 2L12 12M7.5 12L8.5 12L15.5 12L16.5 12M20 19L4 19M16.7071 15.7071L17 16L20 19L17 22L16.7071 22.2929M7.2929 15.7071L7 16L4 19L7 22L7.2929 22.2929");
}

</style>
