<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yko8wbc2a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yko8wbc2a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:smart-watch-square-heart-bold" {...props}></Icon>
