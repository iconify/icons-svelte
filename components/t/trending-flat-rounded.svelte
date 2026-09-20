<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hvvmif0jp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:trending-flat-rounded" {...props}></Icon>
<style>
:global(.hvvmif0jp) {
  fill: currentColor;
  d: path("M18.175 13H4q-.425 0-.712-.288T3 12t.288-.712T4 11h14.175L16.8 9.6q-.3-.3-.288-.7t.313-.7q.3-.275.713-.287t.687.287l3.075 3.1q.3.3.3.7t-.3.7l-3.1 3.1q-.275.275-.687.275T16.8 15.8q-.3-.3-.3-.712t.3-.713z");
}

</style>
