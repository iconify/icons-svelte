<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jj9kn0ifj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="jj9kn0ifj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oi:spreadsheet" {...props}></Icon>
