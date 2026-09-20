<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/plvw6ybat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="plvw6ybat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-enum-member" {...props}></Icon>
