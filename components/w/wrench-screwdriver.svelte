<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yewsoxblj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yewsoxblj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-cyber:wrench-screwdriver" {...props}></Icon>
