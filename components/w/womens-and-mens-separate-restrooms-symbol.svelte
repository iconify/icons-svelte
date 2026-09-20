<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/amsqombxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="amsqombxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:womens-and-mens-separate-restrooms-symbol" {...props}></Icon>
