<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s435_wswk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:tools-ladder-sharp" {...props}></Icon>
<style>
:global(.s435_wswk) {
  fill: currentColor;
  d: path("m4.7 21l5-18h2l-.85 3h5.625l.825-3h2l-5 18h-2l.85-3H7.525L6.7 21zm4.775-10h5.6l.825-3h-5.6zM8.1 16h5.6l.825-3h-5.6z");
}

</style>
