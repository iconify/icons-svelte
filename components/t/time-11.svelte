<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gcy55rw5q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="gcy55rw5q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:time-11" {...props}></Icon>
