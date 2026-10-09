<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lpg9aibwt.css';
import '../../css/q/q3hpk7_5q.css';
import '../../css/u/u-2mnlbwy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="lpg9aibwt"/><path class="q3hpk7_5q"/><path class="u-2mnlbwy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rov-20-bold" {...props}></Icon>
