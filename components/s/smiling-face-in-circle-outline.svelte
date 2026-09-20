<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lich9zb3k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="lich9zb3k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:smiling-face-in-circle-outline" {...props}></Icon>
