<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ysp0zgcvi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ysp0zgcvi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tree-swing" {...props}></Icon>
