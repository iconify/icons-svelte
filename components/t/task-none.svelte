<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p0028ibxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2000,"height":2000};
const content = `<path class="p0028ibxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bpmn:task-none" {...props}></Icon>
