<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o-1lfgblo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:splitscreen-bottom-sharp" {...props}></Icon>
<style>
:global(.o-1lfgblo) {
  fill: currentColor;
  d: path("M3 21v-8h18v8zm0-10V3h18v8zm16-6H5v4h14z");
}

</style>
