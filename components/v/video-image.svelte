<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l5d7zvd5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l5d7zvd5o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:video-image" {...props}></Icon>
