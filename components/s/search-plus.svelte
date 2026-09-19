<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z86z4ciyw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z86z4ciyw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:search-plus" {...props}></Icon>
