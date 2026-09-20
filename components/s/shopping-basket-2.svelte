<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/icoec9b7o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="icoec9b7o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:shopping-basket-2" {...props}></Icon>
