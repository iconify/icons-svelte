<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd8kf1wpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zd8kf1wpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:unsplash-line" {...props}></Icon>
