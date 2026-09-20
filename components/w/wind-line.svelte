<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yk97sd-8b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yk97sd-8b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:wind-line" {...props}></Icon>
