<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ujo66obxz.css';
import '../../css/q/q4yf1rbfs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ujo66obxz"/><path class="q4yf1rbfs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:tab-external-16" {...props}></Icon>
