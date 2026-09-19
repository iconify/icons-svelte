<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fuallir8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fuallir8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:thread-net" {...props}></Icon>
