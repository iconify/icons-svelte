<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b8fddtb-c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="b8fddtb-c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:usb" {...props}></Icon>
