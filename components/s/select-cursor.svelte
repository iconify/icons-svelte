<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7xcghbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="p7xcghbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:select-cursor" {...props}></Icon>
