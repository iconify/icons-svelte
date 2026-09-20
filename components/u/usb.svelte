<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xogyj2ogj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xogyj2ogj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:usb" {...props}></Icon>
