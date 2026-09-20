<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c7pph2bsi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="c7pph2bsi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:token-constant" {...props}></Icon>
