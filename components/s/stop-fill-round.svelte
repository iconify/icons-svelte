<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lr-vo4brq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lr-vo4brq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:stop-fill-round" {...props}></Icon>
