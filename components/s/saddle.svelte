<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2au1nh_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w2au1nh_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:saddle" {...props}></Icon>
