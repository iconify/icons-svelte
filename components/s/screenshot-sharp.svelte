<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t6feptdzo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:screenshot-sharp" {...props}></Icon>
<style>
:global(.t6feptdzo) {
  fill: currentColor;
  d: path("M15.308 15h-1v3.23h-3.231v1h4.23zM8.769 9h1V5.77H13v-1H8.77zM6 22V2h12.077v4.83H19v3.686h-.923V22z");
}

</style>
