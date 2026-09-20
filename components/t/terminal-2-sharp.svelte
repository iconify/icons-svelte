<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sl009tz-t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:terminal-2-sharp" {...props}></Icon>
<style>
:global(.sl009tz-t) {
  fill: currentColor;
  d: path("M12.5 19v-1h7v1zm-6.77-4l-.707-.688L9.329 10L5.023 5.689L5.731 5l5 5z");
}

</style>
