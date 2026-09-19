<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tpy4myw3d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tpy4myw3d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:video-camera-slash-20-solid" {...props}></Icon>
