<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j4ed0ri_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="j4ed0ri_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:strikethrough-16" {...props}></Icon>
