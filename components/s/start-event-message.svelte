<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyl-tabqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="nyl-tabqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:start-event-message" {...props}></Icon>
