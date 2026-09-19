<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vloihibwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":1536};
const content = `<path class="vloihibwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:vcard" {...props}></Icon>
