<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xgx04bw3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xgx04bw3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:wind" {...props}></Icon>
