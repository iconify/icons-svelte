<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="e1fui_b5l"/><path class="pftdq7syg"/><path class="eq71uyb3g"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pop:share-ios" {...props}></Icon>
<style>
:global(.cuyn6tgcc) {
  fill: currentColor;
}

:global(.e1fui_b5l) {
  d: path("M9 3a1 1 0 0 1 2 0v10.5a1 1 0 1 1-2 0z");
}

:global(.eq71uyb3g) {
  d: path("M9.36 2.768a1 1 0 1 1 1.28-1.536l3 2.5a1 1 0 1 1-1.28 1.536zM13 9a1 1 0 1 1 0-2h1c1.623 0 3 1.165 3 2.692v7.616C17 18.835 15.623 20 14 20H6c-1.623 0-3-1.165-3-2.692V9.692C3 8.165 4.377 7 6 7h1a1 1 0 0 1 0 2H6c-.586 0-1 .35-1 .692v7.616c0 .342.414.692 1 .692h8c.586 0 1-.35 1-.692V9.692C15 9.35 14.586 9 14 9z");
}

:global(.pftdq7syg) {
  d: path("M10.64 2.768a1 1 0 1 0-1.28-1.536l-3 2.5a1 1 0 0 0 1.28 1.536z");
}

</style>
