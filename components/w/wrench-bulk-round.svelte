<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vloqe2b9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vloqe2b9q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:wrench-bulk-round" {...props}></Icon>
