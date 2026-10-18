<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gpkq7mu7x.css';
import '../../css/y/yv842m9yr.css';
import '../../css/s/s_1xd9b8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="gpkq7mu7x"/><path class="yv842m9yr"/><path class="s_1xd9b8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:scour-protection-20-bold" {...props}></Icon>
