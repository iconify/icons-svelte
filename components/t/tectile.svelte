<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wvf-ryl3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="wvf-ryl3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:tectile" {...props}></Icon>
