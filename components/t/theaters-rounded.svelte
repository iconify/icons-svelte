<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="liw_rvdbk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:theaters-rounded" {...props}></Icon>
<style>
:global(.liw_rvdbk) {
  fill: currentColor;
  d: path("M5.5 18.5V20q0 .213-.144.356t-.357.144t-.356-.144T4.5 20V4q0-.213.144-.356t.357-.144t.356.144T5.5 4v1.5h3V4.308q0-.343.232-.576t.576-.232h5.384q.344 0 .576.232t.232.576V5.5h3V4q0-.213.144-.356t.357-.144t.356.144T19.5 4v16q0 .213-.144.356t-.357.144t-.356-.144T18.5 20v-1.5h-3v1.192q0 .344-.232.576t-.576.232H9.308q-.343 0-.576-.232t-.232-.576V18.5zm0-1h3v-3h-3zm0-4h3v-3h-3zm0-4h3v-3h-3zm10 8h3v-3h-3zm0-4h3v-3h-3zm0-4h3v-3h-3z");
}

</style>
