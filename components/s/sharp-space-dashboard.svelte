<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mokov8tpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-space-dashboard" {...props}></Icon>
<style>
:global(.mokov8tpu) {
  fill: currentColor;
  d: path("M11 21H3V3h8zm2 0h8v-9h-8zm8-11V3h-8v7z");
}

</style>
