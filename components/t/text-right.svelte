<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xz0560box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xz0560box"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:text-right" {...props}></Icon>
