<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jrox0xb4l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2304,"height":1408};
const content = `<path class="jrox0xb4l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:usb" {...props}></Icon>
