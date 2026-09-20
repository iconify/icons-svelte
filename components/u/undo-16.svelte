<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdwk-ga1f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xdwk-ga1f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:undo-16" {...props}></Icon>
