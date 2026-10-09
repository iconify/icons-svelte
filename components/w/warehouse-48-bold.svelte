<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpnvortse.css';
import '../../css/z/zpkef6b1t.css';
import '../../css/r/roy5ebcho.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mpnvortse"/><path class="zpkef6b1t"/><path class="roy5ebcho"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:warehouse-48-bold" {...props}></Icon>
