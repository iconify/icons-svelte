<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/y/yqtey0bii.css';
import '../../css/o/obyrvxbrs.css';
import '../../css/e/en_6zhbjs.css';
import '../../css/a/aod7xpoai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="yqtey0bii"/><path class="obyrvxbrs wm-a"/><path class="en_6zhbjs wm-k"/><path class="aod7xpoai wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:square-terminal-sketch" {...props}></Icon>
