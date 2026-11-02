<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cc6i9-j6p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cc6i9-j6p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:sweats-line" {...props}></Icon>
