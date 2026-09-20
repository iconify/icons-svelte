<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl118cxej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dl118cxej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:widget-line" {...props}></Icon>
