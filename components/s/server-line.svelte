<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y8lb-0avh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y8lb-0avh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:server-line" {...props}></Icon>
