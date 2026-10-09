<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydzth1mww.css';
import '../../css/v/vf8m8ubqt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ydzth1mww"/><path class="vf8m8ubqt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:wardrobe-20-bold" {...props}></Icon>
