<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cps_kfs1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24,"left":-2,"top":-6};
const content = `<path class="cps_kfs1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="jam:video-camera-f" {...props}></Icon>
