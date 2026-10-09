<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f2nxiyvua.css';
import '../../css/g/gs-niz01e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="f2nxiyvua"/><path class="gs-niz01e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:temperature-48-bold" {...props}></Icon>
