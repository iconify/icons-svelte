<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s52488q7t.css';
import '../../css/d/d58ezqogs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="s52488q7t"/><path class="d58ezqogs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:virtual-desktop" {...props}></Icon>
