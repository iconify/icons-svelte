<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ti33s4bvw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:stat-0-sharp" {...props}></Icon>
<style>
:global(.ti33s4bvw) {
  fill: currentColor;
  d: path("M12 17.577L6.423 12L12 6.423L17.577 12z");
}

</style>
