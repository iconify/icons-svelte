<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zxh2jebzu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zxh2jebzu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:view-grid-plus" {...props}></Icon>
