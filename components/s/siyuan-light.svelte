<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/is0p9ccdm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="is0p9ccdm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:siyuan-light" {...props}></Icon>
