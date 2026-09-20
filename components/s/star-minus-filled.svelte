<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uy9jcwcfv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="uy9jcwcfv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:star-minus-filled" {...props}></Icon>
