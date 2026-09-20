<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u6gofedzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="u6gofedzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:send-cancelled" {...props}></Icon>
