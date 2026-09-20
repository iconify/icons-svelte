<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv2fgj7zw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tv2fgj7zw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:versions-16" {...props}></Icon>
