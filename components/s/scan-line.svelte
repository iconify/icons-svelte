<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dvba2ybat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dvba2ybat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:scan-line" {...props}></Icon>
