<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zt9kaib0k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="zt9kaib0k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:scatter-alignment" {...props}></Icon>
