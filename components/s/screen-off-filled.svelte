<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbf6qccau.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nbf6qccau"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:screen-off-filled" {...props}></Icon>
