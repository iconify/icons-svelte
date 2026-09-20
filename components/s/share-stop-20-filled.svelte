<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tyg02jyrq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:share-stop-20-filled" {...props}></Icon>
<style>
:global(.tyg02jyrq) {
  fill: currentColor;
  d: path("M4.5 4A2.5 2.5 0 0 0 2 6.5v7A2.5 2.5 0 0 0 4.5 16h11a2.5 2.5 0 0 0 2.5-2.5v-7A2.5 2.5 0 0 0 15.5 4zm2.646 3.146a.5.5 0 0 1 .708 0L10 9.293l2.146-2.147a.5.5 0 0 1 .708.708L10.707 10l2.147 2.146a.5.5 0 0 1-.708.708L10 10.707l-2.146 2.147a.5.5 0 0 1-.708-.707L9.293 10L7.146 7.854a.5.5 0 0 1 0-.708");
}

</style>
