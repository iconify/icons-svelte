<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcsm9xb_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":384};
const content = `<path class="lcsm9xb_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:store-24" {...props}></Icon>
