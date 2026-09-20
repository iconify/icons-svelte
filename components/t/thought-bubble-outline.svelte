<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgwgnibyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgwgnibyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:thought-bubble-outline" {...props}></Icon>
