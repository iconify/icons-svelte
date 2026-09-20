<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ni8v59ceb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="ni8v59ceb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:volume-filled" {...props}></Icon>
