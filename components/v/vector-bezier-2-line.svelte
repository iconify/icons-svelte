<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/ga2dxowpa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ga2dxowpa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:vector-bezier-2-line" {...props}></Icon>
