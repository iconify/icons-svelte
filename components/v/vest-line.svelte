<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ux-3xnbyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ux-3xnbyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vest-line" {...props}></Icon>
