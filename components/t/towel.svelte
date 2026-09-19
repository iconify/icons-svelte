<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j--2r6bxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j--2r6bxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:towel" {...props}></Icon>
