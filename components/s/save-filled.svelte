<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4f-aabko.css';
import '../../css/n/nbzxfbcpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y4f-aabko"/><path class="nbzxfbcpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:save-filled" {...props}></Icon>
