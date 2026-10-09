<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h10oigbig.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="h10oigbig"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:skis-48-bold" {...props}></Icon>
