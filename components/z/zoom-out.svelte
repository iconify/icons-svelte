<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cdl6x7-5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="cdl6x7-5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:zoom-out" {...props}></Icon>
