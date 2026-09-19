<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d0ctoy-5l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="d0ctoy-5l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:usb-outline" {...props}></Icon>
