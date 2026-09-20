<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gqt3l_bdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gqt3l_bdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:vending-machine-with-drink-can" {...props}></Icon>
