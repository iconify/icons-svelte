<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i5ad8vbal.css';
import '../../css/v/v3_ntib1p.css';
import '../../css/y/y50a790-m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="i5ad8vbal"/><path class="v3_ntib1p"/><path class="y50a790-m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wifi-48-bold" {...props}></Icon>
