<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv2p86eoi.css';
import '../../css/q/qfryzomdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="tv2p86eoi"/><path class="qfryzomdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-shading-48" {...props}></Icon>
