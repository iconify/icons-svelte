<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lkzb2ebvv"/><path class="j-umdnyjt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:web-inspector-fork" {...props}></Icon>
<style>
:global(.j-umdnyjt) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.857 27.826s3.04-8.366-2.622-12.74c-2.886-2.23-3.581-5.727-2.128-8.244a6.76 6.76 0 0 1 9.237-2.475c3.234 1.867 3.639 5.946 2.475 9.237c-4.643 9.779-11.439 25.904-17.902 24.845c-3.79-.62-.593-14.158-.593-14.158c-4.698 13.881-12.402 17.496-14.613 15.774s-1.605-7.031 1.139-12.22a30.7 30.7 0 0 0 3.018-11.393");
}

:global(.lkzb2ebvv) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.853 13.657a21.479 21.479 0 1 1-9.87-9.196");
}

</style>
