<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1k2omfll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y1k2omfll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:table-filled" {...props}></Icon>
