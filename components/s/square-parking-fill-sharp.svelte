<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d2pkpp_9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:square-parking-fill-sharp" {...props}></Icon>
<style>
:global(.d2pkpp_9r) {
  fill: currentColor;
  d: path("M2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v18a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1M8 7v10a1 1 0 0 0 2 0v-3h2a4 4 0 0 0 0-8H9a1 1 0 0 0-1 1m2 5V8h2a1.999 1.999 0 0 1 1.732 3c-.357.619-1.017 1-1.732 1Z");
}

</style>
