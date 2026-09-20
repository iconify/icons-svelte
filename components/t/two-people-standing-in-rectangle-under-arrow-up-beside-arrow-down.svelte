<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/on3r13bmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="on3r13bmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:two-people-standing-in-rectangle-under-arrow-up-beside-arrow-down" {...props}></Icon>
