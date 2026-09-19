<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fufplvmnw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="fufplvmnw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:zoom-out" {...props}></Icon>
