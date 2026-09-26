<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cv4r938lj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:stop-sharp-fill" {...props}></Icon>
<style>
:global(.cv4r938lj) {
  fill: currentColor;
  d: path("M5 4L19 4C19.5523 4 20 4.4477 20 5L20 19C20 19.5523 19.5523 20 19 20L5 20C4.4477 20 4 19.5523 4 19L4 5C4 4.4477 4.4477 4 5 4Z");
}

</style>
