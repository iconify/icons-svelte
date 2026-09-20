<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g5ltbebwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g5ltbebwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:trending-down-line" {...props}></Icon>
