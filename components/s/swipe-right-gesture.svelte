<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wyk3arcgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wyk3arcgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:swipe-right-gesture" {...props}></Icon>
