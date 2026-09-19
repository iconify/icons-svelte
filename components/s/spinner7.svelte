<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y5os27n7z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y5os27n7z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:spinner7" {...props}></Icon>
