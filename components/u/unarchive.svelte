<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4wb5_did.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="k4wb5_did"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="codicon:unarchive" {...props}></Icon>
