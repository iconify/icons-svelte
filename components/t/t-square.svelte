<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/x/xy71q67bi.css';
import '../../css/f/f3s2fab-i.css';
import '../../css/w/wa2w2_b7p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="xy71q67bi"/><path class="f3s2fab-i"/><path class="wa2w2_b7p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:t-square" {...props}></Icon>
