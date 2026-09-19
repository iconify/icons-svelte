<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a__s2g6zp.css';
import '../../css/w/wbf1jl94t.css';
import '../../css/g/gz1qx8bxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":80,"height":80};
const content = `<g class="a__s2g6zp"><path class="wbf1jl94t"/><path class="gz1qx8bxy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="glyphs:times-bold" {...props}></Icon>
