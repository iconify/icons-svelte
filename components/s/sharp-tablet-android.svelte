<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h1gibbcfq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-tablet-android" {...props}></Icon>
<style>
:global(.h1gibbcfq) {
  fill: currentColor;
  d: path("M21 0H3v24h18zm-7 22h-4v-1h4zm5.25-3H4.75V3h14.5z");
}

</style>
