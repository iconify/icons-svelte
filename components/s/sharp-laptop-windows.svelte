<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mq5p0e3-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-laptop-windows" {...props}></Icon>
<style>
:global(.mq5p0e3-g) {
  fill: currentColor;
  d: path("M20 18v-1h1.99L22 3H2v14h2v1H0v2h24v-2zM4 5h16v10H4z");
}

</style>
