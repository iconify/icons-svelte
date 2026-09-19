<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f4vcp_bxy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="f4vcp_bxy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:start-event-error" {...props}></Icon>
