<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3r-_0bnh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="x3r-_0bnh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:sunny-filled" {...props}></Icon>
