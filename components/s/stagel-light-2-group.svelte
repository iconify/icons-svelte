<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1spidcpk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1spidcpk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:stagel-light-2-group" {...props}></Icon>
