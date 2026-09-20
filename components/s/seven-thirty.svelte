<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<circle class="yqfvb1bwf"/><circle class="f934iu1fb"/><path class="tederrkaj"/><path class="shajr37is"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:seven-thirty" {...props}></Icon>
<style>
:global(.f934iu1fb) {
  cx: 18px;
  cy: 18px;
  r: 14px;
  fill: var(--svg-color--e1e8ed, #e1e8ed);
}

:global(.shajr37is) {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M13 26.661c.479.276 1.09.112 1.367-.366l4.5-7.795a1 1 0 0 0-1.732-1l-4.5 7.795A1 1 0 0 0 13 26.661");
}

:global(.tederrkaj) {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M17 29a1 1 0 1 0 2 0V18a1 1 0 1 0-2 0z");
}

:global(.yqfvb1bwf) {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--99aab5, #99aab5);
}

</style>
