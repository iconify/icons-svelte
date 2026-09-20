<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="co-hv1bmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:text-fields" {...props}></Icon>
<style>
:global(.co-hv1bmq) {
  fill: currentColor;
  d: path("M7.885 19.116v-13h-5V4.885h11.23v1.23h-5v13zm9 0v-8h-3V9.885h7.23v1.23h-3v8z");
}

</style>
