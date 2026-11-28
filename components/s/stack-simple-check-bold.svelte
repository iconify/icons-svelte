<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3u6l-bti.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="r3u6l-bti"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:stack-simple-check-bold" {...props}></Icon>
