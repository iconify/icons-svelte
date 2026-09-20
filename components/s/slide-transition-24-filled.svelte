<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oa0-6fj5g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:slide-transition-24-filled" {...props}></Icon>
<style>
:global(.oa0-6fj5g) {
  fill: currentColor;
  d: path("M4.75 4A2.75 2.75 0 0 0 2 6.75v10.5A2.75 2.75 0 0 0 4.75 20h14.5A2.75 2.75 0 0 0 22 17.25V6.75A2.75 2.75 0 0 0 19.25 4zM6.5 5.5v13H5v-13zm4 13H9v-13h1.5zm5 0H14v-13h1.5z");
}

</style>
