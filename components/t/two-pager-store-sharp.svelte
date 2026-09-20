<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fhlt42bok"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:two-pager-store-sharp" {...props}></Icon>
<style>
:global(.fhlt42bok) {
  fill: currentColor;
  d: path("M14 22v-3h8v3zM2 20V4h20v7h-2V6h-7v5h-2v9zm10.8-2l1-5h8.4l1 5zM5 16h5v-2H5zm0-3h5v-2H5zm0-3h5V8H5zm9 0V8h5v2z");
}

</style>
