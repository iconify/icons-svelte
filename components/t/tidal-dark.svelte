<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/co5zxf4is.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1001,"height":667};
const content = `<path class="co5zxf4is"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:tidal-dark" {...props}></Icon>
