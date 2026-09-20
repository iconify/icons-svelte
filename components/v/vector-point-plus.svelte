<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws8ax8b7w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ws8ax8b7w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:vector-point-plus" {...props}></Icon>
