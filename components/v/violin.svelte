<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yatdorb1e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yatdorb1e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:violin" {...props}></Icon>
