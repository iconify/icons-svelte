<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btc8qxb5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:west-outline-sharp" {...props}></Icon>
<style>
:global(.btc8qxb5q) {
  fill: currentColor;
  d: path("m9 19l-7-7l7-7l1.4 1.4L5.825 11H22v2H5.825l4.6 4.6z");
}

</style>
