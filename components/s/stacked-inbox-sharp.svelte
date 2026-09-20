<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h4iwtsuwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:stacked-inbox-sharp" {...props}></Icon>
<style>
:global(.h4iwtsuwi) {
  fill: currentColor;
  d: path("M5 17V3h18v14zm9-5q.825 0 1.413-.587T16 10h5V5H7v5h5q0 .825.588 1.413T14 12m5 9H1V7h2v12h16z");
}

</style>
