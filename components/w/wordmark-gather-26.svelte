<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xw1_x9b1z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":69,"height":26};
const content = `<path class="xw1_x9b1z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:wordmark-gather-26" {...props}></Icon>
