<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tc8r-qblw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:sim-card" {...props}></Icon>
<style>
:global(.tc8r-qblw) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M8.5 1.75h4.55q1.76 0 3.005 1.245l2.45 2.45Q19.75 6.69 19.75 8.45V18q0 1.76-1.245 3.005T15.5 22.25h-7q-1.76 0-3.005-1.245T4.25 18V6q0-1.76 1.245-3.005T8.5 1.75m4.875 7.5h-2.75q-3.375 0-3.375 3.375v3.25q0 3.375 3.375 3.375h2.75q3.375 0 3.375-3.375v-3.25q0-3.375-3.375-3.375");
}

</style>
