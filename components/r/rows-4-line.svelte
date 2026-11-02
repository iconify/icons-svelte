<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qvx5ekp3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qvx5ekp3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rows-4-line" {...props}></Icon>
