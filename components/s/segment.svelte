<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wm4m64byz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm4m64byz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:segment" {...props}></Icon>
