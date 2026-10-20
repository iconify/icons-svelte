<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n2dshcc3z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:triangle-right-sharp-fill" {...props}></Icon>
<style>
:global(.n2dshcc3z) {
  fill: currentColor;
  d: path("M22 3L22 21C22 21.5523 21.5523 22 21 22L3 22C2.4477 22 2 21.5523 2 21C2 20.7348 2.1054 20.4804 2.2929 20.2929L20.2929 2.2929C20.4804 2.1054 20.7348 2 21 2C21.5523 2 22 2.4477 22 3Z");
}

</style>
