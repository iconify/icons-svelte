<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_si_y0xp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="m_si_y0xp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:semicircle-20" {...props}></Icon>
