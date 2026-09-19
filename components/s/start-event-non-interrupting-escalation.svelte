<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv0dxxbxv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="pv0dxxbxv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:start-event-non-interrupting-escalation" {...props}></Icon>
