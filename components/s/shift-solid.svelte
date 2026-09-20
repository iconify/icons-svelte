<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m_hcr812e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="m_hcr812e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shift-solid" {...props}></Icon>
