<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztm4cfb3x.css';
import '../../css/r/rx-beboiq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="ztm4cfb3x"/><path class="rx-beboiq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:whats-app-outlined" {...props}></Icon>
