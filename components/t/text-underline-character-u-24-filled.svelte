<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zzsmmtegp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-underline-character-u-24-filled" {...props}></Icon>
<style>
:global(.zzsmmtegp) {
  fill: currentColor;
  d: path("M9 5a1 1 0 0 0-2 0v6.5a5 5 0 0 0 10 0V5a1 1 0 1 0-2 0v6.5a3 3 0 1 1-6 0zM7 18a1 1 0 1 0 0 2h10a1 1 0 1 0 0-2z");
}

</style>
