<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zja1g2tpg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zja1g2tpg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:time-zone-fill" {...props}></Icon>
