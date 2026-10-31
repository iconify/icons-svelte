<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsjis7b9r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wsjis7b9r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:sunrise-duotone-round" {...props}></Icon>
