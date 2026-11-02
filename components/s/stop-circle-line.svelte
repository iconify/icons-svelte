<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sz26x-bsk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sz26x-bsk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:stop-circle-line" {...props}></Icon>
