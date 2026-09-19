<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f-zwmjkxi.css';
import '../../css/w/w6h-t2a-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b f-zwmjkxi"/><path class="b w6h-t2a-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:web-components" {...props}></Icon>
