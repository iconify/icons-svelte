<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k2a-x9sbe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k2a-x9sbe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="coolicons:table-cells-split-fill-round" {...props}></Icon>
