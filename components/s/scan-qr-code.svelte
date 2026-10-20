<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smgj5gbjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="smgj5gbjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:scan-qr-code" {...props}></Icon>
