<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tdlieuclz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:stat-0-outline-sharp" {...props}></Icon>
<style>
:global(.tdlieuclz) {
  fill: currentColor;
  d: path("M12 17.577L6.423 12L12 6.423L17.577 12zm0-1.427L16.15 12L12 7.85L7.85 12zM12 12");
}

</style>
