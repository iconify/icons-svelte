<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zb2j65b_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zb2j65b_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:world-line" {...props}></Icon>
