<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xrgurfbrf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xrgurfbrf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair:server-check" {...props}></Icon>
