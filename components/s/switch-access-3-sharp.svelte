<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jpcua_09i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-symbols-light:switch-access-3-sharp" {...props}></Icon>
<style>
:global(.jpcua_09i) {
  fill: currentColor;
  d: path("m10.077 15.154l-.688-.708l1.94-1.946H3v-1h8.329l-1.94-1.946l.688-.708L13.231 12zM3 9.116V6.212h2.904v2.904zm0 8.653v-2.884h2.904v2.884zM10.596 21v-3.002L16.594 12l-5.998-5.998V3H21v4.817h.962v3.654H21V21z");
}

</style>
