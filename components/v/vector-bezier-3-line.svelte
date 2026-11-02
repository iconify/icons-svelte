<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlntbmarp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dlntbmarp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vector-bezier-3-line" {...props}></Icon>
