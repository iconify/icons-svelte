<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wuk76lbpl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wuk76lbpl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tornado-fill" {...props}></Icon>
