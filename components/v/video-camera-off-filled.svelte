<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dq8d756sd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="dq8d756sd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:video-camera-off-filled" {...props}></Icon>
