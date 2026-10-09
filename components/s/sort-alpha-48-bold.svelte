<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ixu--sbaj.css';
import '../../css/z/z4gxs_ibg.css';
import '../../css/x/xoi-lebbd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ixu--sbaj"/><path class="z4gxs_ibg"/><path class="xoi-lebbd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sort-alpha-48-bold" {...props}></Icon>
