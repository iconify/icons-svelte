<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy7xqk_um.css';
import '../../css/u/u_fdmll_m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="xy7xqk_um"/><path class="u_fdmll_m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sidebar-48-bold" {...props}></Icon>
