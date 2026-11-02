<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g3wbyjbbx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zap-fill-sharp" {...props}></Icon>
<style>
:global(.g3wbyjbbx) {
  fill: currentColor;
  d: path("M15 3v7h5a1.002 1.002 0 0 1 .707 1.707l-10 10A1 1 0 0 1 9 21v-7H4a1.002 1.002 0 0 1-.707-1.707l10-10A1 1 0 0 1 15 3");
}

</style>
