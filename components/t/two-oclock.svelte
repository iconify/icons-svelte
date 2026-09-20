<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<circle class="yqfvb1bwf"/><circle class="f934iu1fb"/><path class="y_ptlabie"/><path class="lkxu20wfx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:two-oclock" {...props}></Icon>
<style>
:global(.f934iu1fb) {
  cx: 18px;
  cy: 18px;
  r: 14px;
  fill: var(--svg-color--e1e8ed, #e1e8ed);
}

:global(.lkxu20wfx) {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M26.661 13a1 1 0 0 1-.366 1.366l-7.795 4.5a1 1 0 0 1-1-1.732l7.795-4.5a1 1 0 0 1 1.366.366");
}

:global(.y_ptlabie) {
  fill: var(--svg-color--66757f, #66757f);
  d: path("M19 18a1 1 0 1 1-2 0V7a1 1 0 0 1 2 0z");
}

:global(.yqfvb1bwf) {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--99aab5, #99aab5);
}

</style>
