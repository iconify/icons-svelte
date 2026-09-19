<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whyltiwta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="whyltiwta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="game-icons:steeltoe-boots" {...props}></Icon>
