<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq16c_bps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dq16c_bps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:yahoo-line" {...props}></Icon>
