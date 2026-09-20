<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yxbsrubkq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yxbsrubkq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:usb-port-1-bold" {...props}></Icon>
