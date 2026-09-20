<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="zlikhnb7c"/><path class="xo8pw1bod"/><path class="osp-9gb9h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:siphon" {...props}></Icon>
<style>
:global(.osp-9gb9h) {
  d: path("M128 256h128V128H128v128z");
  fill: var(--svg-color--5884a3, #5884A3);
}

:global(.xo8pw1bod) {
  d: path("M128 129h128V0H128v129z");
  fill: var(--svg-color--6296ba, #6296BA);
}

:global(.zlikhnb7c) {
  d: path("M0 256h129V128H0v128z");
  fill: var(--svg-color--4c728c, #4C728C);
}

</style>
