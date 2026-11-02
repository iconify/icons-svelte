<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfyvobcqu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lfyvobcqu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:space-fill" {...props}></Icon>
