<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/ba8lzwb5c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="ba8lzwb5c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:video-camera" {...props}></Icon>
