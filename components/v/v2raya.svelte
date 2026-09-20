<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xcc91_nac.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="xcc91_nac"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:v2raya" {...props}></Icon>
