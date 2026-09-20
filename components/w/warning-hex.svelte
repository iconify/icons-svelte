<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/s/s3i77ouuq.css';
import '../../css/w/wrt-x_0am.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g transform="translate(-1 -1)" class="bi12bsetm"><path class="s3i77ouuq"/><circle class="wrt-x_0am"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:warning-hex" {...props}></Icon>
