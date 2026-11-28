<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkbrq34zh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rkbrq34zh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:volcano" {...props}></Icon>
