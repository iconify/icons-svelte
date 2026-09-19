<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/c/ce4bvgyxx.css';
import '../../css/a/a6lp9bcmf.css';
import '../../css/z/zwidvqbuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="ce4bvgyxx"/><path class="a6lp9bcmf"/><path class="zwidvqbuw"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:signature" {...props}></Icon>
