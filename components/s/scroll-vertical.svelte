<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_dp74riv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m_dp74riv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:scroll-vertical" {...props}></Icon>
