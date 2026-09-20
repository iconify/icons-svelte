<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uawdfyvtp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uawdfyvtp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="octicon:versions-24" {...props}></Icon>
