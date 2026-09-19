<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ynpw5e4mx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-insert-drive-file" {...props}></Icon>
<style>
:global(.ynpw5e4mx) {
  fill: currentColor;
  d: path("M4.01 2L4 22h16V8l-6-6zM13 9V3.5L18.5 9z");
}

</style>
