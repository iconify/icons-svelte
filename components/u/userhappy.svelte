<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xnn7-0g9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="xnn7-0g9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="quill:userhappy" {...props}></Icon>
