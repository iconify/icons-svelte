<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5f95m3vq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5f95m3vq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:translate-ai" {...props}></Icon>
