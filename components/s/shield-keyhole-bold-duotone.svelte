<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xoqk-f2dc.css';
import '../../css/i/ixj_x3vjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xoqk-f2dc"/><path class="ixj_x3vjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:shield-keyhole-bold-duotone" {...props}></Icon>
