<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-6paieus.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="z-6paieus"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:univention-corporate-server-dark" {...props}></Icon>
