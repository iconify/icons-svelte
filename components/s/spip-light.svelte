<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bpcptns8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bpcptns8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:spip-light" {...props}></Icon>
