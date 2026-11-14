<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/o/oe0dezbyt.css';
import '../../css/a/a1fp7_bvg.css';
import '../../css/z/zb3_-p_9w.css';
import '../../css/w/wca0gqejr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="oe0dezbyt"/><rect class="a1fp7_bvg"/><rect class="zb3_-p_9w"/><path class="wca0gqejr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="evicons:wallbox" {...props}></Icon>
