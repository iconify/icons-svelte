<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_vpf-b4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path clip-rule="evenodd" class="m_vpf-b4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="sidekickicons:video-camera-arrow-up-right-20-solid" {...props}></Icon>
