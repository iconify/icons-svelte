<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gdd_mkcjl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="gdd_mkcjl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:vpn-connection-solid" {...props}></Icon>
