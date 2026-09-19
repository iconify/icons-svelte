<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u-qcybbwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:skip-next" {...props}></Icon>
<style>
:global(.u-qcybbwx) {
  fill: currentColor;
  d: path("m6 18l8.5-6L6 6zM16 6v12h2V6z");
}

</style>
