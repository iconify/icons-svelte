<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj75j-log.css';
import '../../css/f/fdqwsub7z.css';
import '../../css/w/w58xql4qz.css';
import '../../css/y/y_35ybrup.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="bj75j-log"/><path class="fdqwsub7z"/><path class="w58xql4qz"/><path class="y_35ybrup"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wood-pole-20" {...props}></Icon>
