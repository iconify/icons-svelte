<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lb5c5ou6v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lb5c5ou6v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:video-camera-2-fill" {...props}></Icon>
