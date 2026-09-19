<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j7imp4bxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j7imp4bxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:thumbs-down" {...props}></Icon>
