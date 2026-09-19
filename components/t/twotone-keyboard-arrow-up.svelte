<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ibz29_uar"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:twotone-keyboard-arrow-up" {...props}></Icon>
<style>
:global(.ibz29_uar) {
  fill: currentColor;
  d: path("M7.41 15.41L12 10.83l4.59 4.58L18 14l-6-6l-6 6z");
}

</style>
