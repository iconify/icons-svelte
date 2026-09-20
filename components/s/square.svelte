<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="re6m6bgki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:square" {...props}></Icon>
<style>
:global(.re6m6bgki) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M4 5a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1zm2 1v8h8V6z");
}

</style>
