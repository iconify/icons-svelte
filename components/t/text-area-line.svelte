<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqu52_xpu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oqu52_xpu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:text-area-line" {...props}></Icon>
