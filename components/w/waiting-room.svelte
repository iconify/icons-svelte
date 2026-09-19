<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fz06e3bkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fz06e3bkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:waiting-room" {...props}></Icon>
