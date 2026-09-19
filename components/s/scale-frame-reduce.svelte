<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/y/yskvirclu.css';
import '../../css/w/wnu5hjbyz.css';
import '../../css/j/j7-ykzbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="yskvirclu"/><path class="wnu5hjbyz"/><path class="j7-ykzbjp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:scale-frame-reduce" {...props}></Icon>
