<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v5hm9ibup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent:text-align-center-rotate-270-20-filled" {...props}></Icon>
<style>
:global(.v5hm9ibup) {
  fill: currentColor;
  d: path("M4.25 16a.75.75 0 0 1-.75-.75V4.75a.75.75 0 0 1 1.5 0v10.5a.75.75 0 0 1-.75.75m5 2a.75.75 0 0 1-.75-.75V2.75a.75.75 0 0 1 1.5 0v14.5a.75.75 0 0 1-.75.75m4.25-4.75a.75.75 0 0 0 1.5 0v-6.5a.75.75 0 0 0-1.5 0z");
}

</style>
