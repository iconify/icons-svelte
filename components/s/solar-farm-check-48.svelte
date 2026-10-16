<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9ufck1xu.css';
import '../../css/o/oc4c5hbmp.css';
import '../../css/q/qdytrdbev.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="e9ufck1xu"/><path class="oc4c5hbmp"/><path class="qdytrdbev"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-farm-check-48" {...props}></Icon>
