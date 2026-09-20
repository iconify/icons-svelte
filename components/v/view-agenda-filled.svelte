<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vp_rzwbpp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vp_rzwbpp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:view-agenda-filled" {...props}></Icon>
