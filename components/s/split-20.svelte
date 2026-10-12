<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n8c7mwbrw.css';
import '../../css/w/wm5561bcz.css';
import '../../css/i/i8xqukhzb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n8c7mwbrw"/><path class="wm5561bcz"/><path class="i8xqukhzb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:split-20" {...props}></Icon>
