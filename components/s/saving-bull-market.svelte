<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jhum8un3s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="jhum8un3s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:saving-bull-market" {...props}></Icon>
