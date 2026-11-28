<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmm_pxeix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bmm_pxeix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:usb-solid" {...props}></Icon>
