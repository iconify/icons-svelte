<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rd8m2mqxa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rd8m2mqxa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixel:video-camera-solid" {...props}></Icon>
