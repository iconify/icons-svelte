<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plvkgv-rk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="plvkgv-rk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:thread-logo-logo-solid" {...props}></Icon>
