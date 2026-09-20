<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fej4g_csw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fej4g_csw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:socket-io-light" {...props}></Icon>
