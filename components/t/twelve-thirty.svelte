<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<circle class="yqfvb1bwf"/><circle class="f934iu1fb"/><path class="gy_izpc4f"/><path class="zgr6_winf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:twelve-thirty" {...props}></Icon>
<style>
:global(.f934iu1fb) {
  cx: 18px;
  cy: 18px;
  r: 14px;
  fill: var(--svg-color--e1e8ed, #e1e8ed);
}

:global(.gy_izpc4f) {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M17 18a1 1 0 1 1 2 0v11a1 1 0 0 1-2 0z");
}

:global(.yqfvb1bwf) {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--99aab5, #99aab5);
}

:global(.zgr6_winf) {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M19 18a1 1 0 0 1-2 0V9a1 1 0 0 1 2 0z");
}

</style>
