<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rnte2hbdx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rnte2hbdx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:trophy-fill-round" {...props}></Icon>
