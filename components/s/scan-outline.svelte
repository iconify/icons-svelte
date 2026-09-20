<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iblk2mb0y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="iblk2mb0y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lsicon:scan-outline" {...props}></Icon>
