<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w20bu7b2i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-flashlight-off" {...props}></Icon>
<style>
:global(.w20bu7b2i) {
  fill: currentColor;
  d: path("M18 5V2H6v1.17L7.83 5zm-2 6l2-3V7H9.83L16 13.17zM2.81 2.81L1.39 4.22L8 10.83V22h8v-3.17l3.78 3.78l1.41-1.41z");
}

</style>
