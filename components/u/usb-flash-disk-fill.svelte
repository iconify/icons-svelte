<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/arw00qbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="arw00qbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:usb-flash-disk-fill" {...props}></Icon>
