<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/inb8ybb8j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="inb8ybb8j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:text-direction-left-line" {...props}></Icon>
