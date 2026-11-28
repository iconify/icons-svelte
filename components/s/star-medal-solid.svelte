<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tv9yuvbgy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tv9yuvbgy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:star-medal-solid" {...props}></Icon>
