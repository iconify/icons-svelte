<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5jtl4brd.css';
import '../../css/s/slyguszvk.css';
import '../../css/e/ekngixjgr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2000,"height":2000};
const content = `<g class="g5jtl4brd"><path class="slyguszvk"/><path class="ekngixjgr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:send" {...props}></Icon>
