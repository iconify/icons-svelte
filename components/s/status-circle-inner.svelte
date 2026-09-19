<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u5rhxcbqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="u5rhxcbqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:status-circle-inner" {...props}></Icon>
