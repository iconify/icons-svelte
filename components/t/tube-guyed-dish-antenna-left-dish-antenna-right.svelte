<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v5d2v1bhr.css';
import '../../css/z/zisei9b2e.css';
import '../../css/w/wmejmsbwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="v5d2v1bhr"/><path class="zisei9b2e"/><path class="wmejmsbwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:tube-guyed-dish-antenna-left-dish-antenna-right" {...props}></Icon>
