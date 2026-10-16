<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e7m3inbym.css';
import '../../css/c/cbgy24bmz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e7m3inbym"/><path class="cbgy24bmz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:usb-c-20" {...props}></Icon>
