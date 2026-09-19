<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9tr6bcfx.css';
import '../../css/o/ow0crubqn.css';
import '../../css/i/i9ylb1byu.css';
import '../../css/y/yy5gwy9uy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="y9tr6bcfx"><path class="ow0crubqn"/><path class="i9ylb1byu"/><path class="yy5gwy9uy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:temperature-cold" {...props}></Icon>
