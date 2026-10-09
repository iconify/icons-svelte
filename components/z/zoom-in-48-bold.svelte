<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-pfn5jar.css';
import '../../css/l/lq1s_sbrc.css';
import '../../css/v/vhowmnhvx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u-pfn5jar"/><path class="lq1s_sbrc"/><path class="vhowmnhvx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:zoom-in-48-bold" {...props}></Icon>
