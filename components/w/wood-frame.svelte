<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd6a6gjuk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wd6a6gjuk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:wood-frame" {...props}></Icon>
