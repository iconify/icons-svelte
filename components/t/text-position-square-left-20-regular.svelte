<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h3hfelbol"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-position-square-left-20-regular" {...props}></Icon>
<style>
:global(.h3hfelbol) {
  fill: currentColor;
  d: path("M3.5 3a.5.5 0 0 0 0 1h13a.5.5 0 0 0 0-1zM12 6a.5.5 0 0 0 0 1h4.5a.5.5 0 0 0 0-1zm-.5 3.5A.5.5 0 0 1 12 9h4.5a.5.5 0 0 1 0 1H12a.5.5 0 0 1-.5-.5M12 12a.5.5 0 0 0 0 1h4.5a.5.5 0 0 0 0-1zm-9 3.5a.5.5 0 0 1 .5-.5h13a.5.5 0 0 1 0 1h-13a.5.5 0 0 1-.5-.5m1-7a2.5 2.5 0 0 1 5 0v5a.5.5 0 0 0 1 0v-5a3.5 3.5 0 1 0-7 0v5a.5.5 0 0 0 1 0z");
}

</style>
