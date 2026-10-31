<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ff3xd_gyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ff3xd_gyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:tiktok-round" {...props}></Icon>
