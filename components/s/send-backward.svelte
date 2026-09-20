<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tx6vj_dxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tx6vj_dxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:send-backward" {...props}></Icon>
