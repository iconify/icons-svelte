<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g2lh7abvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:sports-mma-sharp" {...props}></Icon>
<style>
:global(.g2lh7abvt) {
  fill: currentColor;
  d: path("M8 19.616v-3.232h8.077v3.231zM7.039 15l-.808-4.05V3.846h10v2.77h1.538v4.296L16.923 15zM9 9.77h4.462V8H9z");
}

</style>
