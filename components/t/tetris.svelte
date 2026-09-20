<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ykrhbm4ed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="ykrhbm4ed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:tetris" {...props}></Icon>
