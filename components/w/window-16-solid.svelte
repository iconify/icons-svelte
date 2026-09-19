<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ils3d3b0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ils3d3b0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:window-16-solid" {...props}></Icon>
