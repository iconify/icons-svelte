<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq_kneo0b.css';
import '../../css/i/i-510_b_l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vq_kneo0b"/><path class="i-510_b_l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:spillway-48" {...props}></Icon>
