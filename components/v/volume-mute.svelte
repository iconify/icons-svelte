<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j82ay1b8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="j82ay1b8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:volume-mute" {...props}></Icon>
