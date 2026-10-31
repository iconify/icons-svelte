<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pvlgjsbrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pvlgjsbrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:server-off-fill-round" {...props}></Icon>
