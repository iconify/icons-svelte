<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxb_c_bxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="yxb_c_bxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:start-event-escalation" {...props}></Icon>
