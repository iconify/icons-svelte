<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":26,"height":26};
const content = `<g clip-rule="evenodd" class="n1lsf0bnc"><path class="qyiexbxhs"/><path class="d6ay7m3xd"/><path class="vx5pkofrw"/><path class="ugl78jfrf"/><path class="hdxpysbbn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:yen-circle" {...props}></Icon>
<style>
:global(.d6ay7m3xd) {
  d: path("M12.293 11.707a1 1 0 0 0 1.414 0l5-5a1 1 0 0 0-1.414-1.414l-5 5a1 1 0 0 0 0 1.414");
}

:global(.hdxpysbbn) {
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

:global(.n1lsf0bnc) {
  fill: currentColor;
  fill-rule: evenodd;
}

:global(.qyiexbxhs) {
  d: path("M13.707 11.707a1 1 0 0 1-1.414 0l-5-5a1 1 0 0 1 1.414-1.414l5 5a1 1 0 0 1 0 1.414");
}

:global(.ugl78jfrf) {
  d: path("M13 12a1 1 0 0 1 1 1v7a1 1 0 1 1-2 0v-7a1 1 0 0 1 1-1");
}

:global(.vx5pkofrw) {
  d: path("M7 12a1 1 0 0 1 1-1h10a1 1 0 1 1 0 2H8a1 1 0 0 1-1-1m0 3.5a1 1 0 0 1 1-1h10a1 1 0 1 1 0 2H8a1 1 0 0 1-1-1");
}

</style>
