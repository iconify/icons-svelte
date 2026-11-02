<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p4xy0vbki.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p4xy0vbki"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:video-camera-fill" {...props}></Icon>
