<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vlm5zeidu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vlm5zeidu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:social-x-line" {...props}></Icon>
