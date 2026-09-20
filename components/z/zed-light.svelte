<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-fuek2tg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="g-fuek2tg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:zed-light" {...props}></Icon>
