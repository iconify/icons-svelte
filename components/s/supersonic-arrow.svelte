<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cgpsre80s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="cgpsre80s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:supersonic-arrow" {...props}></Icon>
