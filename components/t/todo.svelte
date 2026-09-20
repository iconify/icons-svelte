<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ad1opj13q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ad1opj13q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:todo" {...props}></Icon>
