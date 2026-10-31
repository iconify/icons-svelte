<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dxuzy2bmh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dxuzy2bmh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:window-minus-corner-round" {...props}></Icon>
