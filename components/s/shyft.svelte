<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="q0ks9nf-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="arcticons:shyft" {...props}></Icon>
<style>
:global(.q0ks9nf-e) {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m43.5 17.668l-9.543-9.543v6.231h-6.583a6.623 6.623 0 0 0-6.623 6.623s13.206 0 13.206 0v6.231zm-39 12.664l9.543 9.543v-6.231h6.583a6.623 6.623 0 0 0 6.624-6.623s-13.207 0-13.207 0V20.79z");
}

</style>
