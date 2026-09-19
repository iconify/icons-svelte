<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m06gt_svh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m06gt_svh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons-solid:video-camera" {...props}></Icon>
