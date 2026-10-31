<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zca_fftim.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zca_fftim"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:webcam-fill-round" {...props}></Icon>
