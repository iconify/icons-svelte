<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rekgzmbhy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="rekgzmbhy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:spip-dark" {...props}></Icon>
