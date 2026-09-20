<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="t87b9yv9j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:triangle-right" {...props}></Icon>
<style>
:global(.t87b9yv9j) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M12.998 10L6 5.963v8.074zm2.5.866a1 1 0 0 0 0-1.732L5.5 3.365a1 1 0 0 0-1.5.866V15.77a1 1 0 0 0 1.5.866z");
}

</style>
