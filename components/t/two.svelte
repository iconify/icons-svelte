<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yknphmbiv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="yknphmbiv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:two" {...props}></Icon>
