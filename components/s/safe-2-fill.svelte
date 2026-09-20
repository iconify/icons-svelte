<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/giv29obgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="giv29obgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:safe-2-fill" {...props}></Icon>
