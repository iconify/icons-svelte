<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mgh92ubxo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mgh92ubxo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:video-frame-filled" {...props}></Icon>
