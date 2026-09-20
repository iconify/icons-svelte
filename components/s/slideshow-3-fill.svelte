<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p3hd5ph4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p3hd5ph4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:slideshow-3-fill" {...props}></Icon>
