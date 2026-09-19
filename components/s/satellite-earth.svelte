<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wzszqsj-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="wzszqsj-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gis:satellite-earth" {...props}></Icon>
