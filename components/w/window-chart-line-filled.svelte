<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8uve1u_z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8uve1u_z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:window-chart-line-filled" {...props}></Icon>
