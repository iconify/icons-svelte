<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwub5-btk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2000,"height":2000};
const content = `<path class="iwub5-btk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:sub-process-marker" {...props}></Icon>
