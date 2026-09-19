<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkbae3hss.css';
import '../../css/k/ki89_nbwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jkbae3hss"/><path class="ki89_nbwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="circum:volume-high" {...props}></Icon>
