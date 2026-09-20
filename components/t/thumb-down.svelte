<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dfg6x-0ty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dfg6x-0ty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:thumb-down" {...props}></Icon>
