<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="esxn0upma"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:sd-card-sharp" {...props}></Icon>
<style>
:global(.esxn0upma) {
  fill: currentColor;
  d: path("M5 21V8.423L10.423 3H19v18zm4.577-10.23h1V7.345h-1zm2.808 0h1V7.345h-1zm2.807 0h1V7.345h-1z");
}

</style>
