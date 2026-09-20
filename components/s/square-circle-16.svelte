<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy9tbfb-j.css';
import '../../css/p/pj07l70hj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="gy9tbfb-j"/><path class="pj07l70hj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:square-circle-16" {...props}></Icon>
