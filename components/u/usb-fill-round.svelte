<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hck5hdcca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hck5hdcca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:usb-fill-round" {...props}></Icon>
