<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oux_cgbkm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oux_cgbkm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:video-on-ai-line" {...props}></Icon>
