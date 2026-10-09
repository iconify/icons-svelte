<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nf74hnsol.css';
import '../../css/e/e215zmbyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="nf74hnsol"/><path class="e215zmbyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:thermal-storage-48" {...props}></Icon>
