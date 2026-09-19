<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fw054bb7e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fw054bb7e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:yoga" {...props}></Icon>
