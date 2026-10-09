<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p7zsbtb6a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="p7zsbtb6a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:volcano-48" {...props}></Icon>
