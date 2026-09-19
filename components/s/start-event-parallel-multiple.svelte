<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v6vq-lblx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="v6vq-lblx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:start-event-parallel-multiple" {...props}></Icon>
