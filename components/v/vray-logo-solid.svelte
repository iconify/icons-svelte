<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rb4ba92qr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rb4ba92qr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:vray-logo-solid" {...props}></Icon>
