<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uww2inb7w.css';
import '../../css/t/tri5-3hsp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uww2inb7w"/><path class="tri5-3hsp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:security-shield-network" {...props}></Icon>
