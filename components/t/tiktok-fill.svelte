<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejk75kb4z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejk75kb4z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:tiktok-fill" {...props}></Icon>
