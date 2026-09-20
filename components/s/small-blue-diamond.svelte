<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="rdyvtebzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:small-blue-diamond" {...props}></Icon>
<style>
:global(.rdyvtebzo) {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M7.707 18.708a1.003 1.003 0 0 1 0-1.414l9.585-9.586a1.003 1.003 0 0 1 1.414 0l9.587 9.587a1.003 1.003 0 0 1 0 1.414l-9.587 9.585a1.003 1.003 0 0 1-1.414 0z");
}

</style>
