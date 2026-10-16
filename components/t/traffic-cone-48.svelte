<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rl79hl11f.css';
import '../../css/m/m2n9dacld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rl79hl11f"/><path class="m2n9dacld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:traffic-cone-48" {...props}></Icon>
