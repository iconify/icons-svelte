<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ei5vwb4va.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ei5vwb4va"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:upload" {...props}></Icon>
