<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4x5wgpas.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="a4x5wgpas"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:usb-filled" {...props}></Icon>
