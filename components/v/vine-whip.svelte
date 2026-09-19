<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jjblog4ea.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jjblog4ea"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:vine-whip" {...props}></Icon>
