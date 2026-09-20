<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l1y7rt3td.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="l1y7rt3td"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:stopwatch" {...props}></Icon>
