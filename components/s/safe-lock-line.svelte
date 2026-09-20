<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sr7o1ig4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sr7o1ig4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:safe-lock-line" {...props}></Icon>
