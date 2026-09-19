<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fh1o-tbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-turn-left" {...props}></Icon>
<style>
:global(.fh1o-tbgy) {
  fill: currentColor;
  d: path("m6.83 11l1.58 1.59L7 14l-4-4l4-4l1.41 1.41L6.83 9H17v11h-2v-9z");
}

</style>
