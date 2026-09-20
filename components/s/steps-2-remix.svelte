<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvs-ucqty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="lvs-ucqty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:steps-2-remix" {...props}></Icon>
