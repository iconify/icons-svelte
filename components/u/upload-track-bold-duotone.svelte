<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/veh0odx2p.css';
import '../../css/w/wpxm9accj.css';
import '../../css/j/jhnvfxetl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="veh0odx2p"/><path class="wpxm9accj"/><path class="jhnvfxetl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:upload-track-bold-duotone" {...props}></Icon>
