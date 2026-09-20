<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ovbmp5yxh.css';
import '../../css/y/yt306rbnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ovbmp5yxh"/><path class="yt306rbnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:system-search-filled" {...props}></Icon>
