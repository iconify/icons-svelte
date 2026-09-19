<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dlfalxq7l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dlfalxq7l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:sherlock-holmes" {...props}></Icon>
