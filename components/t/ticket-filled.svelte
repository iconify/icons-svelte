<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iyb8srbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iyb8srbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:ticket-filled" {...props}></Icon>
