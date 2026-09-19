<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xmnkvqkdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":552,"height":384};
const content = `<path class="xmnkvqkdl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:vk" {...props}></Icon>
