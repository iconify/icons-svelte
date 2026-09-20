<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u8q-hpbds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:skip-next" {...props}></Icon>
<style>
:global(.u8q-hpbds) {
  fill: currentColor;
  d: path("M16.5 18V6h2v12zm-11 0V6l9 6z");
}

</style>
