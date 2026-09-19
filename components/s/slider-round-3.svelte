<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n1lsf0bnc.css';
import '../../css/z/zxkzwmu0w.css';
import '../../css/r/rfucequyu.css';
import '../../css/q/qor4xqb1b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<g class="n1lsf0bnc"><path class="zxkzwmu0w"/><path class="rfucequyu"/><ellipse class="qor4xqb1b"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:slider-round-3" {...props}></Icon>
