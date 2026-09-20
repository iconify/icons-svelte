<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxqvrzbhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:task-sharp" {...props}></Icon>
<style>
:global(.zxqvrzbhu) {
  fill: currentColor;
  d: path("m10.95 18l5.65-5.65l-1.45-1.45l-4.225 4.225l-2.1-2.1L7.4 14.45zM4 22V2h10l6 6v14zm9-13h5l-5-5z");
}

</style>
