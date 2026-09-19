<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xqr9u7bwd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-camera-indoor" {...props}></Icon>
<style>
:global(.xqr9u7bwd) {
  fill: currentColor;
  d: path("M12 3L4 9v12h16V9zm4 13.06L14 15v2H8v-6h6v2l2-1.06z");
}

</style>
