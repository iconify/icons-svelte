<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/y/yk6pw_bfq.css';
import '../../css/k/kro82vbrq.css';
import '../../css/g/g6o8xobrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="yk6pw_bfq"/><path class="kro82vbrq wm-a"/><path class="g6o8xobrr wm-s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:satellite-dish" {...props}></Icon>
