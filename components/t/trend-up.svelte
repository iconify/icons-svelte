<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/g/ga8mdvb3k.css';
import '../../css/s/sc739gbdn.css';
import '../../css/r/rvymobzlx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ga8mdvb3k"/><path class="sc739gbdn"/><path class="rvymobzlx"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:trend-up" {...props}></Icon>
