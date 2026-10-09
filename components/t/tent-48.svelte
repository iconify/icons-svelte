<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/grbq68bib.css';
import '../../css/a/aqu--qbne.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="grbq68bib"/><path class="aqu--qbne"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:tent-48" {...props}></Icon>
