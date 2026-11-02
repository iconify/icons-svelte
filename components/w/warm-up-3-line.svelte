<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryrab4nvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ryrab4nvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:warm-up-3-line" {...props}></Icon>
