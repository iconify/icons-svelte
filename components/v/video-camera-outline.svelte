<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/un14ccb0l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="un14ccb0l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flowbite:video-camera-outline" {...props}></Icon>
