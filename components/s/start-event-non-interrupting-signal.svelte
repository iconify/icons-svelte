<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yu9-g_lhn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="yu9-g_lhn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:start-event-non-interrupting-signal" {...props}></Icon>
