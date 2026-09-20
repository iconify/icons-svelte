<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ew4hn1bwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ew4hn1bwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:telegraph-key" {...props}></Icon>
