<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f43rry3qf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:shelf-position-sharp" {...props}></Icon>
<style>
:global(.f43rry3qf) {
  fill: currentColor;
  d: path("M4 20v-4.5h16V20zm12.116-5.5V4H20v10.5zM4 14.5V4h3.885v10.5zm4.885 0V4h6.23v10.5z");
}

</style>
