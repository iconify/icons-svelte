<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/btdhc-bgq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="btdhc-bgq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:undo-fill-round" {...props}></Icon>
