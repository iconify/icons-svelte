<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uz2uiw5iv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="uz2uiw5iv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:zhihu-outlined" {...props}></Icon>
