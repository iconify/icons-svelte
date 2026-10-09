<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k10y5ab2w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="k10y5ab2w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:semicircle-48-bold" {...props}></Icon>
