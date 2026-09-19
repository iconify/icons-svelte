<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rzm9y0mnu.css';
import '../../css/n/nxx7kub6k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rzm9y0mnu"/><path clip-rule="evenodd" class="nxx7kub6k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:usb-filled" {...props}></Icon>
