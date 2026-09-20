<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e1e3i_olm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="e1e3i_olm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:step-ca" {...props}></Icon>
