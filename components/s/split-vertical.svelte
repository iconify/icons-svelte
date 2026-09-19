<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf1ga9s9a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="sf1ga9s9a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:split-vertical" {...props}></Icon>
