<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mjfxp-b8c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mjfxp-b8c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-logos:virustotal-logo" {...props}></Icon>
