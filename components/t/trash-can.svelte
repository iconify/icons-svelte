<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/z/zn6rbk6zn.css';
import '../../css/a/azejgcbty.css';
import '../../css/c/clnq2hbxi.css';
import '../../css/w/wt3kbbycd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="zn6rbk6zn"/><path class="azejgcbty"/><path class="clnq2hbxi"/><path class="wt3kbbycd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:trash-can" {...props}></Icon>
