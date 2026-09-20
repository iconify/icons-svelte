<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxd97lx-h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxd97lx-h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:three-waves-solid" {...props}></Icon>
