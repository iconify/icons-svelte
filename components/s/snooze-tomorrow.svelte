<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbmeb0b8h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xbmeb0b8h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:snooze-tomorrow" {...props}></Icon>
