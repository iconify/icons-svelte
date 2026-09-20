<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rho4i-b-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="rho4i-b-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:unreal-engine-logo-solid" {...props}></Icon>
