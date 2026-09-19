<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x6r1jbnmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-splitscreen" {...props}></Icon>
<style>
:global(.x6r1jbnmo) {
  fill: currentColor;
  d: path("M18 4v5H6V4zm2-2H4v9h16zm-2 13v5H6v-5zm2-2H4v9h16z");
}

</style>
