<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owjnpnrlt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="owjnpnrlt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:stumble-upon-2ing-logo-solid" {...props}></Icon>
