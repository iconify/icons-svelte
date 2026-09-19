<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb58uebry.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wb58uebry"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:voc" {...props}></Icon>
