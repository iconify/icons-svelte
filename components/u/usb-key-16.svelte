<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3767cc9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="m3767cc9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:usb-key-16" {...props}></Icon>
