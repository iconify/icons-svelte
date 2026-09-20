<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kvp0xpbst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="kvp0xpbst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:virus-antivirus-remix" {...props}></Icon>
