<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xri0ftdmg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xri0ftdmg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mono-icons:underline" {...props}></Icon>
