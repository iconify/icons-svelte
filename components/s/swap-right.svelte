<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3up2tbet.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3up2tbet"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:swap-right" {...props}></Icon>
