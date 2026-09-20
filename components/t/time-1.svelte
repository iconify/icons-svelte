<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lqepb6b9s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="lqepb6b9s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:time-1" {...props}></Icon>
