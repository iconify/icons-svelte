<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ygvaq_bgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":12,"height":12};
const content = `<path class="ygvaq_bgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="dinkie-icons:seven-of-bamboos-mahjong" {...props}></Icon>
