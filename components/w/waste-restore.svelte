<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/r/rh3zx34ux.css';
import '../../css/o/olx051veg.css';
import '../../css/d/duep00bey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="rh3zx34ux"/><path class="olx051veg"/><path class="duep00bey"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:waste-restore" {...props}></Icon>
