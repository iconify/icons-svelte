<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d8j82fe9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:stop-outline-sharp" {...props}></Icon>
<style>
:global(.d8j82fe9x) {
  fill: currentColor;
  d: path("M8 8v8zm-1 9V7h10v10zm1-1h8V8H8z");
}

</style>
