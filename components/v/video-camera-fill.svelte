<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fe4svgg5d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="fe4svgg5d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:video-camera-fill" {...props}></Icon>
