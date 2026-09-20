<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xy6qukadz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xy6qukadz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:yarr-light" {...props}></Icon>
