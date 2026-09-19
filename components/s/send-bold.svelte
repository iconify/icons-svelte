<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owa54tdfw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="owa54tdfw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:send-bold" {...props}></Icon>
