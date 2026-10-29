<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6-ujrben.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6-ujrben"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:square-minus-solid" {...props}></Icon>
