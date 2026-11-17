<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyt5mjbab.css';
import '../../css/x/xr2-xybln.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lyt5mjbab"/><path class="xr2-xybln"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:solidcraft-light" {...props}></Icon>
