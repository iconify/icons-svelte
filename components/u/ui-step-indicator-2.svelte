<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yonodp2-p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="yonodp2-p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:ui-step-indicator-2" {...props}></Icon>
