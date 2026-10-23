<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmo9a1bwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mmo9a1bwj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:send-horizontal" {...props}></Icon>
