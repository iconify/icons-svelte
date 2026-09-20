<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f95irwlxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f95irwlxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:vercel-fill" {...props}></Icon>
