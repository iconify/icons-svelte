<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n32go5b0t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="n32go5b0t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:square-minus" {...props}></Icon>
