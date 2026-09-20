<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lm2gido9d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:switch-access-outline-sharp" {...props}></Icon>
<style>
:global(.lm2gido9d) {
  fill: currentColor;
  d: path("M7 17V7h10v10zm2-2h6V9H9zm-6 2v-2h2v2zm0-8V7h2v2zm4 12v-2h2v2zM7 5V3h2v2zm8 16v-2h2v2zm0-16V3h2v2zm4 12v-2h2v2zm0-8V7h2v2zm-7 3");
}

</style>
