<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2h37z7fz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="d2h37z7fz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:volcano-48-bold" {...props}></Icon>
