<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tywym2n_w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tywym2n_w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:sort-descending-bulk-round" {...props}></Icon>
