<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfai6u5du.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="mfai6u5du"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:start-event-timer" {...props}></Icon>
