<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbmm7r-un.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="xbmm7r-un"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:squaredribbble" {...props}></Icon>
