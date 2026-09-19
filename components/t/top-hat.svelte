<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b0v99dbvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="b0v99dbvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:top-hat" {...props}></Icon>
