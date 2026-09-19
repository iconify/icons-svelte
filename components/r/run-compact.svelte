<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gaf1vx3va.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="gaf1vx3va"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:run-compact" {...props}></Icon>
