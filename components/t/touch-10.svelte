<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/l/la_v_lbyo.css';
import '../../css/t/tj3-sfldn.css';
import '../../css/r/rhxe-ug5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="la_v_lbyo"/><path class="tj3-sfldn"/><path class="rhxe-ug5q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:touch-10" {...props}></Icon>
