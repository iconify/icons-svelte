<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uka6usb2f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="uka6usb2f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:upload" {...props}></Icon>
