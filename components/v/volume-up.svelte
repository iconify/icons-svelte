<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u50uczbzm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1664,"height":1472};
const content = `<path class="u50uczbzm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:volume-up" {...props}></Icon>
