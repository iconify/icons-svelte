<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgj5w8hcw.css';
import '../../css/v/vd-zhbsrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wgj5w8hcw"/><path class="vd-zhbsrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rupee-48-bold" {...props}></Icon>
