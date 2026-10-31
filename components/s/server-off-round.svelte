<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj5ec_vnd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bj5ec_vnd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:server-off-round" {...props}></Icon>
