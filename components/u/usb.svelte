<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvnh6dndp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="lvnh6dndp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:usb" {...props}></Icon>
