<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l71xewbmm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l71xewbmm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:virus-solid" {...props}></Icon>
