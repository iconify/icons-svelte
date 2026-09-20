<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rn427hbtf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1537,"height":1537};
const content = `<path class="rn427hbtf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:wind-direction-n" {...props}></Icon>
