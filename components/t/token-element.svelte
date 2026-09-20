<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-ziml0pm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="w-ziml0pm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-element" {...props}></Icon>
