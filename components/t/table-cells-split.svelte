<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy63w085a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uy63w085a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:table-cells-split" {...props}></Icon>
