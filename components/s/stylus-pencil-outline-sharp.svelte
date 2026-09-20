<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ckm01-b7q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:stylus-pencil-outline-sharp" {...props}></Icon>
<style>
:global(.ckm01-b7q) {
  fill: currentColor;
  d: path("m6 16l5-13h2l5 13zm2.9-2h6.2L12 5.975zm0 0h6.2zM4 21l1-3h14l1 3z");
}

</style>
