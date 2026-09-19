<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="eyxzjrb5l"/><path class="ao-jgjb9i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ic:sharp-local-see" {...props}></Icon>
<style>
:global(.ao-jgjb9i) {
  fill: currentColor;
  d: path("M22 4h-5.17L15 2H9L7.17 4H2v16h20zM12 17c-2.76 0-5-2.24-5-5s2.24-5 5-5s5 2.24 5 5s-2.24 5-5 5");
}

:global(.eyxzjrb5l) {
  cx: 12px;
  cy: 12px;
  r: 3.2px;
  fill: currentColor;
}

</style>
