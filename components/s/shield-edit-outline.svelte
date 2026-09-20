<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dc20-fbnj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dc20-fbnj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:shield-edit-outline" {...props}></Icon>
