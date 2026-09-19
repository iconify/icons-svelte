<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mrg8lz20a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="mrg8lz20a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:square" {...props}></Icon>
