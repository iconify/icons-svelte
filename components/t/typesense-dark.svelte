<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muk0_xbke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="muk0_xbke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:typesense-dark" {...props}></Icon>
