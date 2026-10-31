<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dyr-ws_tx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dyr-ws_tx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:zodiac-pisces-round" {...props}></Icon>
