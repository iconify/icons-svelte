<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvsq1_bmx.css';
import '../../css/d/daf0krbxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yvsq1_bmx"/><path class="daf0krbxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:router-20-bold" {...props}></Icon>
