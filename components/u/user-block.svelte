<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oun4-vbvq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oun4-vbvq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:user-block" {...props}></Icon>
