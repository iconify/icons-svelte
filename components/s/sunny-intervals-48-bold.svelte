<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/udezbf72w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="udezbf72w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:sunny-intervals-48-bold" {...props}></Icon>
