<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtflctbvl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vtflctbvl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:video-camera-slash-16-solid" {...props}></Icon>
