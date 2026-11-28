<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d5q7f7bps.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d5q7f7bps"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:rows-3" {...props}></Icon>
