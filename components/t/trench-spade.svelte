<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzkkp6bko.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hzkkp6bko"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:trench-spade" {...props}></Icon>
