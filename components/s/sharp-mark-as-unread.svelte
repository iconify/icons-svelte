<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p38pe2b5j"/><path class="ace43_z9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-mark-as-unread" {...props}></Icon>
<style>
:global(.ace43_z9k) {
  fill: currentColor;
  d: path("M5 8v13h17V8zm15 4l-6.5 3.33L7 12v-2l6.5 3.33L20 10z");
}

:global(.p38pe2b5j) {
  fill: currentColor;
  d: path("M16.23 7h4.12L10.5 2L2 6.21V17h2V7.4L10.5 4z");
}

</style>
