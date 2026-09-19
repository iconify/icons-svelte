<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k3drt2bji.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k3drt2bji"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:video-camera" {...props}></Icon>
