<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy3fim5nn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fy3fim5nn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxs:x-circle" {...props}></Icon>
