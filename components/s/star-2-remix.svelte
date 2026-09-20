<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pjp6-toga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="pjp6-toga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:star-2-remix" {...props}></Icon>
