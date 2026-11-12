<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mwapn2_9l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mwapn2_9l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:writefreely-light" {...props}></Icon>
