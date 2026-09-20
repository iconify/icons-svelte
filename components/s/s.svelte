<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydq3irb0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ydq3irb0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:s" {...props}></Icon>
