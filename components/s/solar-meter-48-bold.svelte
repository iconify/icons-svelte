<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rvxin6bpa.css';
import '../../css/d/dnwij0b-f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rvxin6bpa"/><path class="dnwij0b-f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:solar-meter-48-bold" {...props}></Icon>
