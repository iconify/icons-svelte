<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w7by5acwu.css';
import '../../css/g/gzx58mb4y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="w7by5acwu"/><path class="gzx58mb4y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:soldering-iron-20-bold" {...props}></Icon>
