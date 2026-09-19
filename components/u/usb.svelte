<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcbh2obvm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wcbh2obvm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:usb" {...props}></Icon>
