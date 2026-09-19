<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ajvn4_1qw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-align-vertical-bottom" {...props}></Icon>
<style>
:global(.ajvn4_1qw) {
  fill: currentColor;
  d: path("M22 22H2v-2h20zM10 2H7v16h3zm7 6h-3v10h3z");
}

</style>
