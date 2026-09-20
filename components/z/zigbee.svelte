<script>
import Icon from '@iconify/css-svelte';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<defs><radialGradient cx="50%" cy="50%" fx="50%" fy="50%" r="50%" id="ssvg-id-zigbeea"><stop offset="0%" class="iz2-pufkq"/><stop offset="64.215%" class="hgfvi_5ih"/><stop offset="82.382%" class="aip1ikbiu"/><stop offset="100%" class="np3habbnv"/></radialGradient><linearGradient x1="49.895%" y1="100%" x2="49.994%" y2="-1.924%" id="ssvg-id-zigbeeb"><stop offset="0%" class="qneqq27hu"/><stop offset="53.134%" class="r3u2e2byp"/><stop offset="88.757%" class="b32y3nk4z"/><stop offset="100%" class="ize8sqlis"/></linearGradient></defs><path fill="url(#ssvg-id-zigbeea)" class="ktbt139_j"/><path fill="url(#ssvg-id-zigbeeb)" class="qll1ofb9t"/><path class="w5j2894wl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="logos:zigbee" {...props}></Icon>
<style>
:global(.aip1ikbiu) {
  stop-color: var(--svg-color--ae0017, #AE0017);
}

:global(.b32y3nk4z) {
  stop-color: var(--svg-color--fcefe7, #FCEFE7);
}

:global(.hgfvi_5ih) {
  stop-color: var(--svg-color--d5001d, #D5001D);
}

:global(.iz2-pufkq) {
  stop-color: var(--svg-color--dc001f, #DC001F);
}

:global(.ize8sqlis) {
  stop-color: var(--svg-color--fdf7f1, #FDF7F1);
}

:global(.ktbt139_j) {
  d: path("M0 128c0 70.7 57.3 128 128 128s128-57.3 128-128S198.7 0 128 0S0 57.3 0 128z");
}

:global(.np3habbnv) {
  stop-color: var(--svg-color--590e0a, #590E0A);
}

:global(.qll1ofb9t) {
  d: path("M41.864 60.336c0 28.611 38.35 20.78 85.634 20.78c47.285 0 85.635 7.831 85.635-20.78c0-28.512-38.35-51.702-85.635-51.702c-47.285-.1-85.634 23.09-85.634 51.702z");
}

:global(.qneqq27hu) {
  stop-color: var(--svg-color--d4001c, #D4001C);
}

:global(.r3u2e2byp) {
  stop-color: var(--svg-color--ec8a6c, #EC8A6C);
}

:global(.w5j2894wl) {
  d: path("M89.55 201.688c-.201-.301 29.214-32.728 63.648-66.56c34.134-33.832 63.147-63.75 63.247-63.75c-1.104-23.49-18.371-34.835-33.932-36.743c-9.838-2.008-82.623-4.618-123.984 1.807c-7.724.93-15.447 1.948-23.25 3.21c-.304.05-3.365 3.234-6.09 6.524c-2.795 3.374-5.25 6.854-4.996 6.818a753.552 753.552 0 0 1 71.021-6.616a736.201 736.201 0 0 1 72.943.304c.502.402-27.206 31.122-61.34 64.553c-33.932 33.33-64.652 64.15-67.664 67.764c-.2 24.496 20.58 33.933 31.724 36.141c51.702 5.02 103.9 3.224 155.603-5.109c0 0 4.59-5.17 5.144-6.118c.555-.948 4.53-6.898 4.403-6.88c-49.594 7.07-99.158 9.264-148.184 6.562c1.074-.9 1.104-1.204 1.707-1.907z");
  fill: var(--svg-color--fff, #FFF);
}

</style>
