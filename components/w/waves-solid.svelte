<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vty8qkbpx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vty8qkbpx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:waves-solid" {...props}></Icon>
