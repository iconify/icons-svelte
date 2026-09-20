<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ccg9vfo6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ccg9vfo6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-dense-vector" {...props}></Icon>
