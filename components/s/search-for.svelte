<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bck2uobie.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="bck2uobie"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:search-for" {...props}></Icon>
