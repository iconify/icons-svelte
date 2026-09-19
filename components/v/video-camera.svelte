<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fpbx2xb3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":448};
const content = `<path class="fpbx2xb3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:video-camera" {...props}></Icon>
