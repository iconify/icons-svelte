<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vd5kx9nig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="vd5kx9nig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:taobao-circle" {...props}></Icon>
