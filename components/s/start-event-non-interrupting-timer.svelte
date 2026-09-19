<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bfx2w69mn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="bfx2w69mn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:start-event-non-interrupting-timer" {...props}></Icon>
