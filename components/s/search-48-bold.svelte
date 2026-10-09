<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u-pfn5jar.css';
import '../../css/n/nben1wb6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="u-pfn5jar"/><path class="nben1wb6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:search-48-bold" {...props}></Icon>
