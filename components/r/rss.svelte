<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3x82etzf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="x3x82etzf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:rss" {...props}></Icon>
