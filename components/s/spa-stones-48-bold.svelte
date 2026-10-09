<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gy03lmbaj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="gy03lmbaj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:spa-stones-48-bold" {...props}></Icon>
