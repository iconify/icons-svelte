<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itqentznz.css';
import '../../css/l/l_y65ob0n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="itqentznz"/><path class="l_y65ob0n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:usb-c-20-bold" {...props}></Icon>
