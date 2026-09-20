<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2jtvjb0q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":10,"height":10};
const content = `<path class="k2jtvjb0q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:saddle-10" {...props}></Icon>
