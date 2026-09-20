<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hqctu1akv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="hqctu1akv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:video-camera-filled" {...props}></Icon>
