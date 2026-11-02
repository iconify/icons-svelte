<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xu7rcfbcb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xu7rcfbcb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wave-hand-line" {...props}></Icon>
