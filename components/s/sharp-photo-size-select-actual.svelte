<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d0zzatbid"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-photo-size-select-actual" {...props}></Icon>
<style>
:global(.d0zzatbid) {
  fill: currentColor;
  d: path("M23 3H1v18h22zM5 17l3.5-4.5l2.5 3.01L14.5 11l4.5 6z");
}

</style>
