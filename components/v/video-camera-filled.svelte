<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2ebu6bzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2ebu6bzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="griddy-icons:video-camera-filled" {...props}></Icon>
