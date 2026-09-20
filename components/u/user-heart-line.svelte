<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rm-0xthen.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rm-0xthen"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:user-heart-line" {...props}></Icon>
