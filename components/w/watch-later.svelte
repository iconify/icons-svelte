<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l1nyxibxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:watch-later" {...props}></Icon>
<style>
:global(.l1nyxibxw) {
  fill: currentColor;
  d: path("M12 2C6.5 2 2 6.5 2 12s4.5 10 10 10s10-4.5 10-10S17.5 2 12 2m4.2 14.2L11 13V7h1.5v5.2l4.5 2.7z");
}

</style>
