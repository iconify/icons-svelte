<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muo88zbxd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="muo88zbxd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:seagate-light" {...props}></Icon>
