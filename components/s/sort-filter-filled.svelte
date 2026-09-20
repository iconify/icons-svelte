<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcw0y79um.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="wcw0y79um"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:sort-filter-filled" {...props}></Icon>
