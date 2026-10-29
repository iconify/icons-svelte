<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/c/c65boqqfl.css';
import '../../css/q/qfyufmblv.css';
import '../../css/j/jdokwnbqk.css';
import '../../css/r/ro7gmvb1s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="c65boqqfl"/><path class="qfyufmblv wm-shadow"/><path class="jdokwnbqk"/><path class="ro7gmvb1s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:school-engrave" {...props}></Icon>
