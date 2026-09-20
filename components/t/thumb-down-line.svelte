<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy8--92xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fy8--92xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="si:thumb-down-line" {...props}></Icon>
