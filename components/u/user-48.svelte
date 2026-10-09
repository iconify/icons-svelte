<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fdtj74bwx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="fdtj74bwx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:user-48" {...props}></Icon>
