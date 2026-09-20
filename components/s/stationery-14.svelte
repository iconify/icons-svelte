<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j9ogvcbcx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="j9ogvcbcx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="osmic:stationery-14" {...props}></Icon>
