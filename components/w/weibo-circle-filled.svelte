<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j317_ccvk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="j317_ccvk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:weibo-circle-filled" {...props}></Icon>
