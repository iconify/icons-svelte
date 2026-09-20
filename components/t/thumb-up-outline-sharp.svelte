<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="e3nyhxbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:thumb-up-outline-sharp" {...props}></Icon>
<style>
:global(.e3nyhxbrb) {
  fill: currentColor;
  d: path("M7 21V8l7-7l1.85 1.85L14.55 8H23v4.4L19.35 21zm2-2h9l3-7v-2h-9l1.35-5.5L9 8.85zM9 8.85V19zM2 21V8h5v2H4v9h3v2z");
}

</style>
