<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/buhwby_ug.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":432};
const content = `<path class="buhwby_ug"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:washing-machine" {...props}></Icon>
