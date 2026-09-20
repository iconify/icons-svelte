<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nxgt5qbik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="nxgt5qbik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="qlementine-icons:windows-16" {...props}></Icon>
