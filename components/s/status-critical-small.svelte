<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fapfoe3xd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="fapfoe3xd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="grommet-icons:status-critical-small" {...props}></Icon>
