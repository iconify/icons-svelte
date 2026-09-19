<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l8ui-5bzi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l8ui-5bzi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:send-diagonal" {...props}></Icon>
