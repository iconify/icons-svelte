<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tp8o9vbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tp8o9vbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:schneider-electric-light" {...props}></Icon>
