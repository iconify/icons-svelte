<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w4ma5v20c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":30};
const content = `<path class="w4ma5v20c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="wi:wind-beaufort-6" {...props}></Icon>
