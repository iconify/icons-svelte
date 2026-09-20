<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tqzu5893t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="tqzu5893t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:vending-machine" {...props}></Icon>
