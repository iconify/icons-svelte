<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d3wg6qbpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d3wg6qbpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:signal-3g" {...props}></Icon>
