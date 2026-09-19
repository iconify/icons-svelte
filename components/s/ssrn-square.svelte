<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mh21-8b1c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="mh21-8b1c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="academicons:ssrn-square" {...props}></Icon>
