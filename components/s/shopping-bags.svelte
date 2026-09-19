<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/e/e6cpddcyw.css';
import '../../css/r/ry3rr2hev.css';
import '../../css/e/eu2bi-boo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="e6cpddcyw"/><path class="ry3rr2hev"/><path class="eu2bi-boo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:shopping-bags" {...props}></Icon>
