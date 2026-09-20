<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fs8hqxbve.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fs8hqxbve"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:triangle-down-filled" {...props}></Icon>
