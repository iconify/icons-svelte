<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="l081hdcpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione-monotone:up-left-arrow" {...props}></Icon>
<style>
:global(.l081hdcpk) {
  fill: currentColor;
  d: path("M53.212 10.788c-11.715-11.717-30.711-11.717-42.426 0c-11.715 11.715-11.715 30.708 0 42.425c11.715 11.715 30.711 11.715 42.426 0c11.717-11.717 11.717-30.711 0-42.425m-14.25 35.21L25.509 32.717L18 40.131V17.999h22.057l-7.432 7.564L46 38.953z");
}

</style>
