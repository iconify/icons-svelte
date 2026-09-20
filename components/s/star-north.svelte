<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfd20o4wp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfd20o4wp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:star-north" {...props}></Icon>
