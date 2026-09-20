<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3spyu8-g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3spyu8-g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:size-xs" {...props}></Icon>
