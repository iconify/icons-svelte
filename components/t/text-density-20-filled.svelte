<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yh7bf5bkv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-density-20-filled" {...props}></Icon>
<style>
:global(.yh7bf5bkv) {
  fill: currentColor;
  d: path("M10.5 2a.5.5 0 0 1 .5.5v15a.5.5 0 0 1-1 0v-15a.5.5 0 0 1 .5-.5M9 5H2.5a.5.5 0 0 0 0 1H9zm0 3H2.5a.5.5 0 0 0 0 1H9zm0 3H2.5a.5.5 0 0 0 0 1H9zm0 3H2.5a.5.5 0 0 0 0 1H9zm7.5 0H12v-3h4.5a1.5 1.5 0 0 1 0 3m0-5H12V6h4.5a1.5 1.5 0 0 1 0 3");
}

</style>
