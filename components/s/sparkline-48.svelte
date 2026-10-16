<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vu9cx5bea.css';
import '../../css/c/cnom9xbgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="vu9cx5bea"/><path class="cnom9xbgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sparkline-48" {...props}></Icon>
