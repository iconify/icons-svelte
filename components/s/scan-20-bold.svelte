<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxm0nzb2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="yxm0nzb2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scan-20-bold" {...props}></Icon>
