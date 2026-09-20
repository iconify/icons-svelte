<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfy4_i41q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rfy4_i41q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wet-line" {...props}></Icon>
