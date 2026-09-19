<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2swcvilm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":464,"height":448};
const content = `<path class="y2swcvilm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:wikipedia" {...props}></Icon>
