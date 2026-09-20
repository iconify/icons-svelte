<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xqlt9f4ny.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xqlt9f4ny"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:tidal-logo-solid" {...props}></Icon>
