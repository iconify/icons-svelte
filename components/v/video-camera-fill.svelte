<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gr9d0ie7x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="gr9d0ie7x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:video-camera-fill" {...props}></Icon>
