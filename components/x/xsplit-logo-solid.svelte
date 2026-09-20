<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-67u_bfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="p-67u_bfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:xsplit-logo-solid" {...props}></Icon>
