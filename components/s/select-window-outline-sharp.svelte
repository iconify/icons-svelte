<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mbflgx3yd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:select-window-outline-sharp" {...props}></Icon>
<style>
:global(.mbflgx3yd) {
  fill: currentColor;
  d: path("M3 20.808v-11h4V3.192h14v11h-4v6.616zm1-1h12v-7H4zm13-6.616h3v-7H8v3.616h9z");
}

</style>
