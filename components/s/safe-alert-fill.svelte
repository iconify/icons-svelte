<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdpw95c_r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdpw95c_r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:safe-alert-fill" {...props}></Icon>
