<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jobs7tb5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jobs7tb5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:tower-flag" {...props}></Icon>
