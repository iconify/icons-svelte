<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pm8pbtlmi.css';
import '../../css/l/liz4x11yp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pm8pbtlmi"/><path class="liz4x11yp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:temu" {...props}></Icon>
