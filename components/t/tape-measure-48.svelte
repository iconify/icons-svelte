<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ow6zdh7dh.css';
import '../../css/m/m0tcvtbkn.css';
import '../../css/g/g179ywr-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ow6zdh7dh"/><path class="m0tcvtbkn"/><path class="g179ywr-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tape-measure-48" {...props}></Icon>
