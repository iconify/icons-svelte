<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nx3t7-i1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nx3t7-i1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:snooze-week" {...props}></Icon>
