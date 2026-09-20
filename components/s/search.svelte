<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwdl0x74e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dwdl0x74e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mynaui:search" {...props}></Icon>
