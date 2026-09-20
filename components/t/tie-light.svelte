<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vxlvwzb3q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vxlvwzb3q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:tie-light" {...props}></Icon>
