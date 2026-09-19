<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fi682gbey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1472};
const content = `<path class="fi682gbey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:table-o" {...props}></Icon>
