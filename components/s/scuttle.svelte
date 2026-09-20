<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n0p_qpq5m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="n0p_qpq5m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:scuttle" {...props}></Icon>
