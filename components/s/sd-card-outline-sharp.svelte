<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="usk5-2bcj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:sd-card-outline-sharp" {...props}></Icon>
<style>
:global(.usk5-2bcj) {
  fill: currentColor;
  d: path("M9.577 10.77h1V7.345h-1zm2.808 0h1V7.345h-1zm2.807 0h1V7.345h-1zM5 21V8.423L10.423 3H19v18zm1-1h12V4h-7.15L6 8.85zm0 0h12z");
}

</style>
