<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cm_rohcmr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="cm_rohcmr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ep:video-camera-filled" {...props}></Icon>
