<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bf1b6zb8e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bf1b6zb8e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:upload-gloss" {...props}></Icon>
