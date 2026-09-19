<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e8lzn6bab.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="e8lzn6bab"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:tablet" {...props}></Icon>
