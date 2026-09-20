<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq661j3rq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iq661j3rq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:terminal-box-line" {...props}></Icon>
