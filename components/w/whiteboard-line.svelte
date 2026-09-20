<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xfvpunchv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xfvpunchv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:whiteboard-line" {...props}></Icon>
