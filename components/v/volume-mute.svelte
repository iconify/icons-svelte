<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c-cu5rj5k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:volume-mute" {...props}></Icon>
<style>
:global(.c-cu5rj5k) {
  fill: currentColor;
  d: path("M7 15V9h4l5-5v16l-5-5z");
}

</style>
