<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihdvcd13a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ihdvcd13a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scan-48-bold" {...props}></Icon>
