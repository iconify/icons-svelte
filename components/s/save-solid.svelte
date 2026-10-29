<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrtfb8xyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mrtfb8xyf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:save-solid" {...props}></Icon>
