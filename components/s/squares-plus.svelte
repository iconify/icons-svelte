<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i-ye4wb-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i-ye4wb-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:squares-plus" {...props}></Icon>
