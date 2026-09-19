<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<circle class="bgatx5byk"/><path class="u6_-_fblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="emojione:upwards-button" {...props}></Icon>
<style>
:global(.bgatx5byk) {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--4fd1d9, #4fd1d9);
}

:global(.u6_-_fblr) {
  fill: var(--svg-color--fff, #fff);
  d: path("M52 38L32 18L12 38z");
}

</style>
