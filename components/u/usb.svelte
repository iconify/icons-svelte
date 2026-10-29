<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_bi1nufz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w_bi1nufz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:usb" {...props}></Icon>
