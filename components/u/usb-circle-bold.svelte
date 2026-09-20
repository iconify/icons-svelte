<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b7unxbbtx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b7unxbbtx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:usb-circle-bold" {...props}></Icon>
