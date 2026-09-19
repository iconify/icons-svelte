<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/g/g63mxooxl.css';
import '../../css/f/f0p3izb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":17,"height":17};
const content = `<g transform="translate(1)" class="n1lsf0bnc"><path class="g63mxooxl"/><ellipse class="f0p3izb7e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si-glyph:ying-yang" {...props}></Icon>
