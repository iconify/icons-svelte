<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzvr3j-wy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:values-compass" {...props}></Icon>
<style>
:global(.uzvr3j-wy) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q0-4.246 3.002-7.248T12 1.75t7.248 3.002T22.25 12t-3.002 7.248T12 22.25t-7.248-3.002T1.75 12m12.278-4.268Q13.415 6.457 12 6.457T9.972 7.732l-1.585 3.291q-.47.977 0 1.953l1.585 3.292q.613 1.275 2.028 1.275t2.028-1.275l1.585-3.292q.47-.976 0-1.952z");
}

</style>
