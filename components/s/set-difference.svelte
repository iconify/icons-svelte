<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sevsyxb6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uix-solid:set-difference" {...props}></Icon>
<style>
:global(.sevsyxb6v) {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M1.75 12q-.001-2.9 2.049-4.951Q5.85 4.998 8.75 4.998q1.786 0 3.25.778q1.464-.778 3.25-.778q2.9 0 4.951 2.051T22.25 12q.001 2.9-2.049 4.951q-2.051 2.051-4.951 2.051q-1.786 0-3.25-.778q-1.464.778-3.25.778q-2.9 0-4.951-2.051T1.75 12m1.75 0q0 2 2 2t2-2t-2-2t-2 2");
}

</style>
