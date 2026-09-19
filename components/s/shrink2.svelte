<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a3v6v0bca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="a3v6v0bca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:shrink2" {...props}></Icon>
