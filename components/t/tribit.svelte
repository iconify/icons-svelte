<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zyt6voa4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:tribit" {...props}></Icon>
<style>
:global(.zyt6voa4n) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.285 16.982a4.859 4.859 0 1 1 4.208-7.288l13.715 23.755a4.859 4.859 0 1 1-8.416 0L33.507 9.693a4.859 4.859 0 1 1 4.208 7.288z");
}

</style>
