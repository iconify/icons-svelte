<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uxhd3fa8c.css';
import '../../css/l/l19np-bgg.css';
import '../../css/e/e3xg10aou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="uxhd3fa8c"/><path class="l19np-bgg"/><path class="e3xg10aou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:windmill-48-bold" {...props}></Icon>
