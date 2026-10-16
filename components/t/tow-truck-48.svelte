<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnnymsbii.css';
import '../../css/l/lai5ftb8v.css';
import '../../css/d/d_2bnvy8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="wnnymsbii"/><path class="lai5ftb8v"/><path class="d_2bnvy8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tow-truck-48" {...props}></Icon>
