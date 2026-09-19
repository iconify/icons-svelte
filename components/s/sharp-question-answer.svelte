<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="kjakrkdqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-question-answer" {...props}></Icon>
<style>
:global(.kjakrkdqh) {
  fill: currentColor;
  d: path("M22 6h-3v9H6v3h12l4 4zm-5 7V2H2v15l4-4z");
}

</style>
