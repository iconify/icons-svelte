<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ncbeau7-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:table-lamp-sharp" {...props}></Icon>
<style>
:global(.ncbeau7-m) {
  fill: currentColor;
  d: path("M13 20.5v-1h7v1zm3-2.77V6.578h-5.308v3.654H4.398L7.128 4h3.564v1.577H17v12.154z");
}

</style>
