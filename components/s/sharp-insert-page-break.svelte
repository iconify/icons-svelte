<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hxjod0b5s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-insert-page-break" {...props}></Icon>
<style>
:global(.hxjod0b5s) {
  fill: currentColor;
  d: path("M4 17h16v5H4zm16-9l-6-6H4.01L4 11h16zm-7 1V3.5L18.5 9zm-4 4h6v2H9zm8 0h6v2h-6zM1 13h6v2H1z");
}

</style>
