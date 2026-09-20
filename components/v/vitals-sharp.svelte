<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ssvn3j4no"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols:vitals-sharp" {...props}></Icon>
<style>
:global(.ssvn3j4no) {
  fill: currentColor;
  d: path("M1 13v-2h5.7L9 17.1l6-15.825L18.7 11H23v2h-5.7L15 6.9L9 22.725L5.3 13z");
}

</style>
