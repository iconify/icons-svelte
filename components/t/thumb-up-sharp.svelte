<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5ct4aboz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:thumb-up-sharp" {...props}></Icon>
<style>
:global(.l5ct4aboz) {
  fill: currentColor;
  d: path("M8 21V8l7-7l1.85 1.85L15.55 8H23v4.4L19.35 21zm-6 0V8h4v13z");
}

</style>
