<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhz5xzb0h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zhz5xzb0h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:verizon" {...props}></Icon>
