<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/huogh35_q.css';
import '../../css/d/d_3u0kb9m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="huogh35_q"/><path class="d_3u0kb9m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:smiley-smile-2" {...props}></Icon>
