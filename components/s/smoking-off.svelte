<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r43hsbbqq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r43hsbbqq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:smoking-off" {...props}></Icon>
