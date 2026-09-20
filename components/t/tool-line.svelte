<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxmz_6bpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nxmz_6bpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tool-line" {...props}></Icon>
