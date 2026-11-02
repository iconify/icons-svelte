<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x908zntiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x908zntiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:tower-crane-fill" {...props}></Icon>
