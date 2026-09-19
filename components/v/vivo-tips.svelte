<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="okdg34bcs"/><path class="nagopmbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:vivo-tips" {...props}></Icon>
<style>
:global(.nagopmbki) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.28 18.296s-.786-8.599 9.888-9.982");
}

:global(.okdg34bcs) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.005 43.5h12.188m-19.5-28.667C12.429 8.353 17.39 4.5 24.099 4.5s11.67 3.852 13.406 10.333s-1.502 13.125-7.312 16.48v7.312H18.005v-7.312c-7.65-3.654-9.049-10-7.312-16.48");
}

</style>
