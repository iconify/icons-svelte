<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwuams2xl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="bwuams2xl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:vib" {...props}></Icon>
