<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qqhfcj8qs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qqhfcj8qs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:video-camera-slash-solid" {...props}></Icon>
