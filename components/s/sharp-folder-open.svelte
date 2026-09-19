<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bkzc8qb3g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-folder-open" {...props}></Icon>
<style>
:global(.bkzc8qb3g) {
  fill: currentColor;
  d: path("M22 6H12l-2-2H2v16h20zm-2 12H4V8h16z");
}

</style>
