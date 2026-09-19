<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rpc52qb8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-javascript" {...props}></Icon>
<style>
:global(.rpc52qb8h) {
  fill: currentColor;
  d: path("M12 15v-2h1.5v.5h2v-1H12V9h5v2h-1.5v-.5h-2v1H17V15zM9 9v4.5H7.5v-1H6V15h4.5V9z");
}

</style>
