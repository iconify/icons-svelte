<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fk4hx468i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-keyboard-arrow-right" {...props}></Icon>
<style>
:global(.fk4hx468i) {
  fill: currentColor;
  d: path("M8.59 16.59L13.17 12L8.59 7.41L10 6l6 6l-6 6z");
}

</style>
