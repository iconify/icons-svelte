<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dl_4qt1zu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dl_4qt1zu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:spiderweb" {...props}></Icon>
