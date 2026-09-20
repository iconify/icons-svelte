<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yvtm0sbtl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="yvtm0sbtl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:shipment-remove-remix" {...props}></Icon>
