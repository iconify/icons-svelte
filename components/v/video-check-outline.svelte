<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qv_z1rwws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qv_z1rwws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:video-check-outline" {...props}></Icon>
