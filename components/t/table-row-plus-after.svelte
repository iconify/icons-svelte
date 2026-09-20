<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhx2ux-1l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zhx2ux-1l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:table-row-plus-after" {...props}></Icon>
