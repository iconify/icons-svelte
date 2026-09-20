<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="m9bovp1uu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:slash-forward-12-filled" {...props}></Icon>
<style>
:global(.m9bovp1uu) {
  fill: currentColor;
  d: path("M7.464 1.03a.75.75 0 0 1 .507.932l-2.501 8.5a.75.75 0 0 1-1.44-.424l2.503-8.5a.75.75 0 0 1 .93-.507");
}

</style>
