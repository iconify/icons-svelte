<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="v6ulq6e-s"/><path clip-rule="evenodd" class="yr1mq_boa"/><path class="xedf9ccsf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:triangle-down-filled-off" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.v6ulq6e-s) {
  fill-rule: evenodd;
  d: path("M10.866 15.499a1 1 0 0 1-1.732 0l-5.769-10A1 1 0 0 1 4.231 4H15.77a1 1 0 0 1 .866 1.5z");
}

:global(.xedf9ccsf) {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

:global(.yr1mq_boa) {
  fill-rule: evenodd;
  d: path("M3.365 5.5A1 1 0 0 1 4.231 4H15.77a1 1 0 0 1 .866 1.5l-5.769 9.999a1 1 0 0 1-1.732 0zM10 10.997L12.306 7H7.694z");
}

</style>
