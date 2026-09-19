<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wy_lx-scp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wy_lx-scp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:swap-right-outline" {...props}></Icon>
