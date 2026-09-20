<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v9li6m6qm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<path class="v9li6m6qm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:volume-low" {...props}></Icon>
