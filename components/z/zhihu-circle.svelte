<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xg9d7cc2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="xg9d7cc2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:zhihu-circle" {...props}></Icon>
