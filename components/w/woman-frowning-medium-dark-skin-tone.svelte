<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":36,"height":36};
const content = `<path class="vctw93b8d"/><path class="wk5hybmkm"/><path class="m7dafn76w"/><path class="y10rjqbxs"/><path class="ady1z5c0l"/><path class="vi3m1o-ff"/><path class="asg3-yb7f"/><path class="vsxwv5bbi"/><path class="y0wifzfpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="twemoji:woman-frowning-medium-dark-skin-tone" {...props}></Icon>
<style>
:global(.ady1z5c0l) {
  fill: var(--svg-color--60352a, #60352a);
  d: path("M27 4H9v1H8v6c6 0 6-6 6-6s2 7 14 7V5z");
}

:global(.asg3-yb7f) {
  fill: var(--svg-color--60352a, #60352a);
  d: path("M14 17a1 1 0 0 1-1-1v-1a1 1 0 0 1 2 0v1a1 1 0 0 1-1 1m8 0a1 1 0 0 1-1-1v-1a1 1 0 1 1 2 0v1a1 1 0 0 1-1 1");
}

:global(.m7dafn76w) {
  fill: var(--svg-color--af7e57, #af7e57);
  d: path("M15 22v6a3 3 0 1 0 6 0v-6z");
}

:global(.vctw93b8d) {
  fill: var(--svg-color--60352a, #60352a);
  d: path("M19 0c-1.721 0-3.343.406-4.793 1.111A7 7 0 0 0 13 1a7 7 0 0 0-7 7v12h.018C6.201 26.467 11.489 31.656 18 31.656S29.799 26.467 29.982 20H30v-9c0-6.075-4.925-11-11-11");
}

:global(.vi3m1o-ff) {
  fill: var(--svg-color--7450a8, #7450a8);
  d: path("M9 32h1v4H9zm17 0h1v4h-1z");
}

:global(.vsxwv5bbi) {
  fill: var(--svg-color--915a34, #915a34);
  d: path("M19 20.5h-2a.5.5 0 0 1 0-1h2a.5.5 0 0 1 0 1");
}

:global(.wk5hybmkm) {
  fill: var(--svg-color--9268ca, #9268ca);
  d: path("M27 27H9a4 4 0 0 0-4 4v5h26v-5a4 4 0 0 0-4-4");
}

:global(.y0wifzfpx) {
  fill: var(--svg-color--df1f32, #df1f32);
  d: path("M15 24s1.001-2 3-2s3 2 3 2z");
}

:global(.y10rjqbxs) {
  fill: var(--svg-color--af7e57, #af7e57);
  d: path("M9 5v12c0 4.971 4.029 9 9 9s9-4.029 9-9V5z");
}

</style>
