<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y1_5z5cjw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y1_5z5cjw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:skull-crossed-bones" {...props}></Icon>
